LeetCode
======== 

Up to date (2015-05-20), there are `197` Algorithms / `12` Database / `4` Shell problems on [LeetCode Online Judge](https://oj.leetcode.com/).
The number of problems is increasing recently.
Here is the classification of all `213` problems.
For extra problems and solutions, you can see my [LintCode](https://github.com/kamyu104/LintCode) repo.
I'll keep updating for full summary and better solutions. Stay tuned for updates.
(Notes: "📖" means you have to buy the book from LeetCode. )

--- 
Algorithms
====

* [Bit Manipulation](https://github.com/kamyu104/LeetCode#bit-manipulation)
* [Array](https://github.com/kamyu104/LeetCode#array)
* [String](https://github.com/kamyu104/LeetCode#string)
* [Linked List](https://github.com/kamyu104/LeetCode#linked-list)
* [Stack](https://github.com/kamyu104/LeetCode#stack)
* [Heap](https://github.com/kamyu104/LeetCode#heap)
* [Tree](https://github.com/kamyu104/LeetCode#tree)
* [Hash Table](https://github.com/kamyu104/LeetCode#hash-table)
* [Data Structure](https://github.com/kamyu104/LeetCode#data-structure)
* [Math](https://github.com/kamyu104/LeetCode#math)
* [Two Pointer](https://github.com/kamyu104/LeetCode#two-pointer)
* [Sort](https://github.com/kamyu104/LeetCode#sort)
* [Brute Force Search](https://github.com/kamyu104/LeetCode#brute-force-search)
* [Divide and Conquer](https://github.com/kamyu104/LeetCode#divide-and-conquer)
* [Binary Search](https://github.com/kamyu104/LeetCode#binary-search)
* [Breadth-First Search](https://github.com/kamyu104/LeetCode#breadth-first-search)
* [Depth-First Search](https://github.com/kamyu104/LeetCode#depth-first-search)
* [Dynamic Programming](https://github.com/kamyu104/LeetCode#dynamic-programming)
* [Backtracking](https://github.com/kamyu104/LeetCode#backtracking)
* [Greedy](https://github.com/kamyu104/LeetCode#greedy)


Database
===

* [SQL](https://github.com/kamyu104/LeetCode#sql)


Shell
===

* [Shell Script](https://github.com/kamyu104/LeetCode#shell-script)

---

##Bit Manipulation
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
136 | [Single Number](https://oj.leetcode.com/problems/single-number/) | [Python](./Python/single-number.py) | _O(n)_       | _O(1)_          | Medium         ||
137 | [Single Number II](https://oj.leetcode.com/problems/single-number-ii/) | [Python](./Python/single-number-ii.py) | _O(n)_ | _O(1)_          | Medium         ||
190 | [Reverse Bits](https://oj.leetcode.com/problems/reverse-bits/)  | [Python](./Python/reverse-bits.py) | _O(n)_        | _O(1)_          | Easy           ||
191  |[Number of 1 Bits](https://oj.leetcode.com/problems/number-of-1-bits/) | [Python](./Python/number-of-1-bits.py) | _O(m)_ | _O(1)_          | Easy           ||
201 | [Bitwise AND of Numbers Range](https://leetcode.com/problems/bitwise-and-of-numbers-range/) | [Python](./Python/bitwise-and-of-numbers-range.py) | _O(1)_ | _O(1)_ | Medium ||

--- 

##Array

  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
15 | [3 Sum](https://oj.leetcode.com/problems/3sum/)         | [Python](./Python/3sum.py)       | _O(n^2)_        | _O(1)_          | Medium         ||
16 | [3 Sum Closest](https://oj.leetcode.com/problems/3sum-closest/) | [Python](./Python/3sum-closest.py)| _O(n^2)_       | _O(1)_          | Medium         ||
26 | [Remove Duplicates from Sorted Array](https://oj.leetcode.com/problems/remove-duplicates-from-sorted-array/)| [Python](./Python/remove-duplicates-from-sorted-array.py) | _O(n)_       | _O(1)_         | Easy           ||
27 | [Remove Element](https://oj.leetcode.com/problems/remove-element/) | [Python](./Python/remove-element.py) | _O(n)_      | _O(1)_         | Easy           ||
31 | [Next Permutation](https://oj.leetcode.com/problems/next-permutation/)| [Python](./Python/next-permutation.py) | _O(n)_  | _O(1)_          | Medium         || Tricky
41 | [First Missing Positive](https://oj.leetcode.com/problems/first-missing-positive/)| [Python](./Python/first-missing-positive.py) | _O(n)_ | _O(1)_ | Hard         || Tricky
48 | [Rotate Image](https://oj.leetcode.com/problems/rotate-image/)   | [Python](./Python/rotate-image.py) | _O(n^2)_      | _O(1)_         | Medium         ||
54 | [Spiral Matrix](https://oj.leetcode.com/problems/spiral-matrix/) | [Python](./Python/spiral-matrix.py) | _O(m * n)_    | _O(1)_         | Medium         ||
59 | [Spiral Matrix II](https://oj.leetcode.com/problems/spiral-matrix-ii/) | [Python](./Python/spiral-matrix-ii.py) | _O(m * n)_ | _O(1)_      | Medium         ||
66 | [Plus One](https://oj.leetcode.com/problems/plus-one/)      | [Python](./Python/plus-one.py)   | _O(n)_           | _O(1)_         | Easy           || 
73 | [Set Matrix Zeroes](https://oj.leetcode.com/problems/set-matrix-zeroes/) | [Python](./Python/set-matrix-zeroes.py) | _O(m * n)_ | _O(1)_    | Medium         ||
80 | [Remove Duplicates from Sorted Array II](https://oj.leetcode.com/problems/remove-duplicates-from-sorted-array-ii/)| [Python](./Python/remove-duplicates-from-sorted-array-ii.py) | _O(n)_       | _O(1)_         | Medium         ||
118 | [Pascal's Triangle](https://oj.leetcode.com/problems/pascals-triangle/)| [Python](./Python/pascals-triangle.py) | _O(n^2)_ | _O(n)_        | Easy           || 
119 | [Pascal's Triangle II](https://oj.leetcode.com/problems/pascals-triangle-ii/)| [Python](./Python/pascals-triangle-ii.py) | _O(n^2)_ | _O(n)_  | Easy           ||
121 | [Best Time to Buy and Sell Stock](https://oj.leetcode.com/problems/best-time-to-buy-and-sell-stock/)| [Python](./Python/best-time-to-buy-and-sell-stock.py) | _O(n)_ | _O(1)_ | Medium ||
128 | [Longest Consecutive Sequence](https://oj.leetcode.com/problems/longest-consecutive-sequence/)| [Python](./Python/longest-consecutive-sequence.py) | _O(n)_ | _O(n)_ | Hard         || Tricky
157 | [Read N Characters Given Read4](https://oj.leetcode.com/problems/read-n-characters-given-read4/) | [Python](./Python/read-n-characters-given-read4.py) | _O(n)_ | _O(1)_ | Easy           |📖|
158 | [Read N Characters Given Read4 II - Call multiple times](https://oj.leetcode.com/problems/read-n-characters-given-read4-ii-call-multiple-times/) | [Python](./Python/read-n-characters-given-read4-ii-call-multiple-times.py) | _O(n)_ | _O(1)_ | Hard |📖|
163 | [Missing Ranges](https://oj.leetcode.com/problems/missing-ranges/)| [Python](./Python/missing-ranges.py) | _O(n)_      | _O(1)_          | Medium         | 📖 |
169 | [Majority Element](https://oj.leetcode.com/problems/majority-element/) | [Python](./Python/majority-element.py) | _O(n)_ | _O(1)_          | Easy           |
189 | [Rotate Array](https://oj.leetcode.com/problems/rotate-array/)   | [Python](./Python/rotate-array.py) | _O(n)_        | _O(1)_         | Easy           ||
209 | [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/) | [Python] (./Python/minimum-size-subarray-sum.py) | _O(n)_ | _O(1)_ |  Medium ||

--- 

##String
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
5| [Longest Palindromic Substring](https://oj.leetcode.com/problems/longest-palindromic-substring/) | [Python](./Python/longest-palindromic-substring.py) | _O(n)_ | _O(n)_ |  Medium || `Manacher's Algorithm`
6| [ZigZag Conversion](https://oj.leetcode.com/problems/zigzag-conversion/) | [Python](./Python/zigzag-conversion.py) | _O(n)_ | _O(1)_        | Easy           ||
8| [String to Integer (atoi)](https://oj.leetcode.com/problems/string-to-integer-atoi/) | [Python](./Python/string-to-integer-atoi.py) | _O(n)_ | _O(1)_ | Easy      ||
14| [Longest Common Prefix](https://oj.leetcode.com/problems/longest-common-prefix/) | [Python](./Python/longest-common-prefix.py) | _O(n1 + n2 + ...)_   | _O(1)_  | Easy           ||
28| [Implement strStr()](https://oj.leetcode.com/problems/implement-strstr/) | [Python](./Python/implement-strstr.py) | _O(n + m)_   | _O(m)_  | Easy           || `KMP Algorithm`
38| [Count and Say](https://oj.leetcode.com/problems/compare-version-numbers/) | [Python](./Python/compare-version-numbers.py)| _O(n * 2^n)_  | _O(2^n)_        | Easy           ||
43| [Multiply Strings](https://oj.leetcode.com/problems/multiply-strings/) | [Python](./Python/multiply-strings.py) | _O(m * n)_ | _O(m + n)_  | Medium         ||
58| [Length of Last Word](https://oj.leetcode.com/problems/length-of-last-word/) | [Python](./Python/length-of-last-word.py) | _O(n)_   | _O(1)_  | Easy           ||
67| [Add Binary](https://oj.leetcode.com/problems/add-binary/)    | [Python](./Python/add-binary.py) | _O(n)_          | _O(1)_          | Easy           ||
68| [Text Justification](https://oj.leetcode.com/problems/text-justification/) | [Python](./Python/text-justification.py) | _O(n)_ | _O(1)_      | Hard           ||
125| [Valid Palindrome](https://oj.leetcode.com/problems/valid-palindrome/) | [Python](./Python/valid-palindrome.py) | _O(n)_  | _O(1)_         | Easy           ||
151| [Reverse Words in a String](https://oj.leetcode.com/problems/reverse-words-in-a-string/) | [Python](./Python/reverse-words-in-a-string.py) | _O(n)_ | _O(n)_ | Medium         ||
161| [One Edit Distance](https://oj.leetcode.com/problems/one-edit-distance/) | [Python](./Python/one-edit-distance.py) | _O(m + n)_ | _O(1)_    | Medium         |📖|
165| [Compare Version Numbers](https://oj.leetcode.com/problems/count-and-say/) | [Python](./Python/count-and-say.py) | _O(n)_ | _O(1)_ | Easy     ||
186| [Reverse Words in a String II](https://oj.leetcode.com/problems/reverse-words-in-a-string-ii/) | [Python](./Python/reverse-words-in-a-string-ii.py) | _O(n)_ | _O(1)_ | Medium         | 📖 |
205| [Isomorphic Strings](https://oj.leetcode.com/problems/isomorphic-strings/) | [Python](./Python/isomorphic-strings.py) | _O(n)_ | _O(1)_       | Easy           ||    

--- 

##Linked List
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
2| [Add Two Numbers](https://oj.leetcode.com/problems/add-two-numbers/) | [Python](./Python/add-two-numbers.py) | _O(n)_   | _O(1)_          | Medium         ||
24| [Swap Nodes in Pairs](https://oj.leetcode.com/problems/swap-nodes-in-pairs/)| [Python](./Python/swap-nodes-in-pairs.py)   | _O(n)_          | _O(1)_          | Medium         ||
25| [Reverse Nodes in k-Group](https://oj.leetcode.com/problems/reverse-nodes-in-k-group/)| [Python](./Python/reverse-nodes-in-k-group.py) | _O(n)_       | _O(1)_         | Hard         ||
61| [Rotate List](https://oj.leetcode.com/problems/rotate-list/)| [Python](./Python/rotate-list.py)   | _O(n)_          | _O(1)_          | Medium         ||  
82| [Remove Duplicates from Sorted List II](https://oj.leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)| [Python](./Python/remove-duplicates-from-sorted-list-ii.py) | _O(n)_       | _O(1)_         | Medium         ||
83| [Remove Duplicates from Sorted List](https://oj.leetcode.com/problems/remove-duplicates-from-sorted-list/)| [Python](./Python/remove-duplicates-from-sorted-list.py) | _O(n)_       | _O(1)_         | Easy           ||
92| [Reverse Linked List II](https://oj.leetcode.com/problems/reverse-linked-list-ii/)| [Python](./Python/reverse-linked-list-ii.py) | _O(n)_       | _O(1)_         | Medium         || 
138| [Copy List with Random Pointer](https://oj.leetcode.com/problems/copy-list-with-random-pointer/) | [Python](./Python/copy-list-with-random-pointer.py) | _O(n)_   | _O(1)_          | Hard         ||
160| [Intersection of Two Linked Lists](https://oj.leetcode.com/problems/intersection-of-two-linked-lists/)| [Python](./Python/intersection-of-two-linked-lists.py) | _O(m + n)_ | _O(1)_         | Easy           ||
203| [Remove Linked List Elements](https://oj.leetcode.com/problems/remove-linked-list-elements/)| [Python](./Python/remove-linked-list-elements.py) | _O(n)_       | _O(1)_         | Easy         || 
206| [Reverse Linked List](https://oj.leetcode.com/problems/reverse-linked-list/)| [Python](./Python/reverse-linked-list.py) | _O(n)_       | _O(1)_         | Easy         || 

--- 

##Stack
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
20| [Valid Parentheses](https://oj.leetcode.com/problems/valid-parentheses/)| [Python](./Python/valid-parentheses.py) | _O(n)_        | _O(n)_          | Easy           ||
32| [Longest Valid Parentheses](https://oj.leetcode.com/problems/longest-valid-parentheses/)| [Python](./Python/longest-valid-parentheses.py) | _O(n)_ | _O(1)_ | Hard   ||
71| [Simplify Path](https://oj.leetcode.com/problems/simplify-path/)| [Python](./Python/simplify-path.py) | _O(n)_        | _O(n)_          | Medium         ||
101| [Symmetric Tree](https://oj.leetcode.com/problems/symmetric-tree/)| [Python](./Python/symmetric-tree.py) | _O(n)_      | _O(h)_          | Easy           ||
150| [Evaluate Reverse Polish Notation](https://oj.leetcode.com/problems/evaluate-reverse-polish-notation/)| [Python](./Python/evaluate-reverse-polish-notation.py)| _O(n)_| _O(n)_| Medium          ||
155| [Min Stack](https://oj.leetcode.com/problems/min-stack/)     | [Python](./Python/min-stack.py)  | _O(n)_          | _O(1)_          | Easy           ||
173| [Binary Search Tree Iterator](https://oj.leetcode.com/problems/binary-search-tree-iterator/) | [Python](./Python/binary-search-tree-iterator.py) | _O(1)_| _O(h)_| Medium ||   

--- 

##Heap
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
23| [Merge k Sorted Lists](https://oj.leetcode.com/problems/merge-k-sorted-lists/) | [Python](./Python/merge-k-sorted-lists.py) | _O(nlogk)_| _O(k)_| Hard          ||

--- 

##Tree
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
94 | [Binary Tree Inorder Traversal](https://oj.leetcode.com/problems/binary-tree-inorder-traversal/)  | [Python](./Python/binary-tree-inorder-traversal.py) | _O(n)_| _O(1)_| Medium           || `Morris Traversal` | 
99 | [Recover Binary Search Tree](https://oj.leetcode.com/problems/recover-binary-search-tree/) | [Python](./Python/recover-binary-search-tree.py) | _O(n)_| _O(1)_| Hard  || `Morris Traversal` 
144 | [Binary Tree Preorder Traversal](https://oj.leetcode.com/problems/binary-tree-preorder-traversal/) | [Python](./Python/binary-tree-preorder-traversal.py) | _O(n)_| _O(1)_| Medium || `Morris Traversal` 
145 | [Binary Tree Postorder Traversal](https://oj.leetcode.com/problems/binary-tree-postorder-traversal/) | [Python](./Python/binary-tree-postorder-traversal.py) | _O(n)_| _O(1)_| Hard  || `Morris Traversal` 
208 | [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/) | [Python](./Python/implement-trie-prefix-tree.py) | _O(n)_ | _O(1)_ | Medium || Trie
211 | [Add and Search Word - Data structure design ](https://leetcode.com/problems/add-and-search-word-data-structure-design/) | [C++](./C++/add-and-search-word-data-structure-design.cpp) [Python](./Python/add-and-search-word-data-structure-design.py) | _O(min(n, h))_ | _O(min(n, h))_ | Medium || Trie, DFS
212| [Word Search II](https://oj.leetcode.com/problems/word-search-ii/) | [C++](./C++/word-search-ii.cpp) [Python](./Python/word-search-ii.py) | _O(m * n * l)_ | _O(l)_  | Hard         | LintCode | Trie, DFS

--- 

##Hash Table
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
1| [Two Sum](https://oj.leetcode.com/problems/two-sum/)      | [Python](./Python/two-sum.py)      | _O(n)_         | _O(n)_          | Medium         ||
3| [Longest Substring Without Repeating Characters](https://oj.leetcode.com/problems/longest-substring-without-repeating-characters/) | [Python](./Python/longest-substring-without-repeating-characters.py) | _O(n)_ | _O(1)_ | Medium ||
18| [4 Sum](https://oj.leetcode.com/problems/4sum/)         |[Python](./Python/4sum.py)        | _O(n^2 * p)_    | _O(n^2 * p)_    | Medium         ||
30| [Substring with Concatenation of All Words](https://oj.leetcode.com/problems/substring-with-concatenation-of-all-words/) | [Python](./Python/substring-with-concatenation-of-all-words.py) | _O(m * n * k)_ | _O(n * k)_ | Hard          ||
36| [Valid Sudoku](https://oj.leetcode.com/problems/valid-sudoku/) | [Python](./Python/valid-sudoku.py) | _O(n^2)_         | _O(n)_          | Easy           ||
49| [Anagrams](https://oj.leetcode.com/problems/anagrams/)     | [Python](./Python/anagrams.py)   | _O(n)_          | _O(n)_          | Medium         ||
76| [Minimum Window Substring](https://oj.leetcode.com/problems/minimum-window-substring/) | [Python](./Python/minimum-window-substring.py) | _O(n)_ | _O(k)_ | Hard          ||
149| [Max Points on a Line](https://oj.leetcode.com/problems/max-points-on-a-line/) | [Python](./Python/max-points-on-a-line.py) | _O(n^2)_ | _O(n)_ | Hard          ||
159| [Longest Substring with At Most Two Distinct Characters](https://oj.leetcode.com/problems/longest-substring-with-at-most-two-distinct-characters/)| [Python](./Python/longest-substring-with-at-most-two-distinct-characters.py) | _O(n^2)_ | _O(1)_ | Hard         |📖|
170| [Two Sum III - Data structure design](https://oj.leetcode.com/problems/two-sum-iii-data-structure-design/) | [Python](./Python/two-sum-iii-data-structure-design.py) | _O(n)_ | _O(n)_ | Easy | 📖 |
187| [Repeated DNA Sequences](https://oj.leetcode.com/problems/repeated-dna-sequences/) | [Python](./Python/repeated-dna-sequences.py) | _O(n)_       | _O(n)_          | Medium         ||
202| [Happy Number](https://oj.leetcode.com/problems/happy-number/)      | [Python](./Python/happy-number.py)   | _O(k)_  | _O(k)_          | Easy          ||
204| [Count Primes](https://oj.leetcode.com/problems/count-primes/)  | [Python](./Python/count-primes.py) | _O(n)_        | _O(n)_          | Easy           ||

--- 

##Data Structure
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
146| [LRU Cache](https://oj.leetcode.com/problems/lru-cache/)     | [Python](./Python/lru-cache.py)  | _O(1)_          | _O(n)_          | Hard         ||

--- 

##Math
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
7| [Reverse Integer](https://oj.leetcode.com/problems/reverse-integer/) | [Python](./Python/reverse-integer.py) | _O(logn)_ | _O(1)_         | Easy           ||
9| [Palindrome Number](https://oj.leetcode.com/problems/palindrome-number/) | [Python](./Python/palindrome-number.py) | _O(1)_ | _O(1)_        | Easy           ||
12| [Integer to Roman](https://oj.leetcode.com/problems/integer-to-roman/) | [Python](./Python/integer-to-roman.py) | _O(n)_ | _O(1)_          | Medium         ||
13| [Roman to Integer](https://oj.leetcode.com/problems/roman-to-integer/) | [Python](./Python/roman-to-integer.py) | _O(n)_ | _O(1)_          | Easy           ||
29| [Divide Two Integers](https://oj.leetcode.com/problems/divide-two-integers/) | [Python](./Python/divide-two-integers.py)    | _O(logn)_       | _O(1)_         | Medium         ||
60| [Permutation Sequence](https://oj.leetcode.com/problems/permutation-sequence/) | [Python](./Python/permutation-sequence.py) | _O(n^2)_ | _O(n)_  | Medium         || `Cantor Ordering`
65| [Valid Number](https://oj.leetcode.com/problems/valid-number/) | [Python](./Python/valid-number.py) | _O(n)_         | _O(1)_          | Hard           || `Automata`
89| [Gray Code](https://oj.leetcode.com/problems/gray-code/)     | [Python](./Python/gray-code.py)  | _O(2^n)_        | _O(1)_          | Medium         ||
166| [Fraction to Recurring Decimal](https://oj.leetcode.com/problems/fraction-to-recurring-decimal/) | [Python](./Python/fraction-to-recurring-decimal.py)  | _O(logn)_ | _O(1)_ | Medium         ||
168| [Excel Sheet Column Title](https://oj.leetcode.com/problems/excel-sheet-column-title/) | [Python](./Python/excel-sheet-column-title.py) | _O(logn)_ | _O(1)_ | Easy ||
171| [Excel Sheet Column Number](https://oj.leetcode.com/problems/excel-sheet-column-number/) | [Python](./Python/excel-sheet-column-number.py) | _O(n)_ | _O(1)_ | Easy  ||
172| [Factorial Trailing Zeroes](https://oj.leetcode.com/problems/factorial-trailing-zeroes/) | [Python](./Python/factorial-trailing-zeroes.py)  | _O(logn)_ | _O(1)_ | Easy         ||

--- 

##Sort
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
21| [Merge Two Sorted Lists](https://oj.leetcode.com/problems/merge-two-sorted-lists/)| [Python](./Python/merge-two-sorted-lists.py) | _O(n)_ | _O(1)_ | Easy         ||
56| [Merge Intervals](https://oj.leetcode.com/problems/merge-intervals/)| [Python](./Python/merge-intervals.py) | _O(nlogn)_  | _O(1)_        | Hard           ||
57| [Insert Interval](https://oj.leetcode.com/problems/insert-interval/)| [Python](./Python/insert-interval.py) | _O(n)_    | _O(1)_          | Hard           ||
75| [Sort Colors](https://oj.leetcode.com/problems/sort-colors/)   | [Python](./Python/sort-colors.py) | _O(n)_         | _O(1)_          | Medium         ||
88| [Merge Sorted Array](https://oj.leetcode.com/problems/merge-sorted-array/)| [Python](./Python/merge-sorted-array.py) | _O(n)_ | _O(1)_       | Easy           ||
147| [Insertion Sort List](https://oj.leetcode.com/problems/insertion-sort-list/)|[Python](./Python/insertion-sort-list.py) | _O(n^2)_ | _O(1)_    | Medium         ||
148| [Sort List](https://oj.leetcode.com/problems/sort-list/)     | [Python](./Python/sort-list.py)  | _O(nlogn)_      | _O(logn)_       | Medium         ||
164| [Maximum Gap](https://oj.leetcode.com/problems/maximum-gap/)   | [Python](./Python/maximum-gap.py)| _O(n)_          | _O(n)_          | Hard           || Tricky 
179| [Largest Number](https://oj.leetcode.com/problems/largest-number/) | [Python](./Python/largest-number.py) | _O(nlogn)_   | _O(1)_        | Medium         ||

---

##Two Pointer
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
19| [Remove Nth Node From End of List](https://oj.leetcode.com/problems/remove-nth-node-from-end-of-list/)| [Python](./Python/remove-nth-node-from-end-of-list.py) | _O(n)_       | _O(1)_         | Easy         || 
86| [Partition List](https://oj.leetcode.com/problems/partition-list/)| [Python](./Python/partition-list.py) | _O(n)_       | _O(1)_         | Medium         || 
141| [Linked List Cycle](https://oj.leetcode.com/problems/linked-list-cycle/)| [Python](./Python/linked-list-cycle.py) | _O(n)_ | _O(1)_         | Medium         || 
142| [Linked List Cycle II](https://oj.leetcode.com/problems/linked-list-cycle-ii/)| [Python](./Python/linked-list-cycle-ii.py) | _O(n)_ | _O(1)_   | Medium         ||
143| [Reorder List](https://oj.leetcode.com/problems/reorder-list/)| [Python](./Python/reorder-list.py) | _O(n)_          |  _O(1)_         | Medium         ||  
167| [Two Sum II - Input array is sorted](https://oj.leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | [Python](./Python/two-sum-ii-input-array-is-sorted.py) | _O(n)_   | _O(1)_         | Medium         | 📖 |

---

##Brute Force Search
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
17| [Letter Combinations of a Phone Number](https://oj.leetcode.com/problems/letter-combinations-of-a-phone-number/)| [Python](./Python/letter-combinations-of-a-phone-number.py) | _O(n * 4^n)_ | _O(n)_ | Medium ||
46| [Permutations](https://oj.leetcode.com/problems/permutations/)| [Python](./Python/permutations.py) | _O(n!)_         | _O(n)_          | Medium         ||
47| [Permutations II](https://oj.leetcode.com/problems/permutations-ii/)| [Python](./Python/permutations-ii.py) | _O(n!)_   | _O(n)_          | Hard           ||
78| [Subsets](https://oj.leetcode.com/problems/subsets/)       | [Python](./Python/subsets.py)    | _O(n * 2^n)_    | _O(1)_          | Medium         ||
90| [Subsets II](https://oj.leetcode.com/problems/subsets-ii/)    | [Python](./Python/subsets-ii.py) | _O(n * 2^n)_    | _O(1)_          | Medium         ||

--- 

##Divide and Conquer
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
95| [Unique Binary Search Trees II](https://oj.leetcode.com/problems/unique-binary-search-trees-ii/) | [Python](./Python/unique-binary-search-trees-ii.py) | _O(4^n / n^(3/2)_      | _O(4^n / n^(3/2)_         | Medium         ||
98| [Validate Binary Search Tree](https://oj.leetcode.com/problems/validate-binary-search-tree/)|[Python](./Python/validate-binary-search-tree.py)| _O(n)_ | _O(1)_ | Medium ||
100| [Same Tree](https://oj.leetcode.com/problems/same-tree/)      |[Python](./Python/same-tree.py)  | _O(n)_          | _O(h)_        | Easy          ||
104| [Maximum Depth of Binary Tree](https://oj.leetcode.com/problems/maximum-depth-of-binary-tree/)|[Python](./Python/maximum-depth-of-binary-tree.py)| _O(n)_ | _O(h)_ | Easy ||
105| [Construct Binary Tree from Preorder and Inorder Traversal](https://oj.leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | [Python](./Python/construct-binary-tree-from-preorder-and-inorder-traversal.py) | _O(n)_        | _O(n)_          | Medium   ||
106| [Construct Binary Tree from Inorder and Postorder Traversal](https://oj.leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) | [Python](./Python/construct-binary-tree-from-inorder-and-postorder-traversal.py) | _O(n)_        | _O(n)_          | Medium         ||
108| [Convert Sorted Array to Binary Search Tree](https://oj.leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | [Python](./Python/convert-sorted-array-to-binary-search-tree.py) | _O(n)_        | _O(logn)_          | Medium         ||
109| [Convert Sorted List to Binary Search Tree](https://oj.leetcode.com/problems/convert-sorted-list-to-binary-search-tree/) | [Python](./Python/convert-sorted-list-to-binary-search-tree.py) | _O(n)_        | _O(logn)_          | Medium         ||
110| [Balanced Binary Tree](https://oj.leetcode.com/problems/balanced-binary-tree/) | [Python](./Python/balanced-binary-tree.py) | _O(n)_| _O(h)_   | Easy           ||
111| [Minimum Depth of Binary Tree](https://oj.leetcode.com/problems/minimum-depth-of-binary-tree/)|[Python](./Python/minimum-depth-of-binary-tree.py)| _O(n)_ | _O(h)_ | Easy ||
114| [Flatten Binary Tree to Linked List](https://oj.leetcode.com/problems/flatten-binary-tree-to-linked-list/)|[Python](./Python/flatten-binary-tree-to-linked-list.py)| _O(n)_        | _O(h)_          | Medium         ||
116| [Populating Next Right Pointers in Each Node](https://oj.leetcode.com/problems/populating-next-right-pointers-in-each-node/)|[Python](./Python/populating-next-right-pointers-in-each-node.py)| _O(n)_ | _O(1)_ | Medium ||
124| [Binary Tree Maximum Path Sum](https://oj.leetcode.com/problems/binary-tree-maximum-path-sum/)| [Python](./Python/binary-tree-maximum-path-sum.py) | _O(n)_| _O(h)_| Hard  ||  
129| [Sum Root to Leaf Numbers](https://oj.leetcode.com/problems/sum-root-to-leaf-numbers/) | [Python](./Python/sum-root-to-leaf-numbers.py) | _O(n)_ | _O(h)_ | Medium ||
156| [Binary Tree Upside Down](https://oj.leetcode.com/problems/binary-tree-upside-down/) | [Python](./Python/binary-tree-upside-down.py) | _O(n)_ | _O(1)_ | Medium    |📖| 

--- 

##Binary Search
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
4| [Median of Two Sorted Arrays](https://oj.leetcode.com/problems/median-of-two-sorted-arrays/) | [Python](./Python/median-of-two-sorted-arrays.py) | _O(log(m + n))_ | _O(1)_ | Hard         ||
33| [Search in Rotated Sorted Array](https://oj.leetcode.com/problems/search-in-rotated-sorted-array/) | [Python](./Python/search-in-rotated-sorted-array.py) | _O(logn)_ | _O(1)_   | Hard         ||
34| [Search for a Range](https://oj.leetcode.com/problems/search-for-a-range/) | [Python](./Python/search-for-a-range.py) | _O(logn)_ | _O(1)_   | Medium         ||
35| [Search Insert Position](https://oj.leetcode.com/problems/search-insert-position/) | [Python](./Python/search-insert-position.py) | _O(logn)_ | _O(1)_   | Medium         ||
50| [Pow(x, n)](https://oj.leetcode.com/problems/powx-n/)     | [Python](./Python/powx-n.py)     | _O(logn)_       | _O(logn)_       | Medium         ||
69| [Sqrt(x)](https://oj.leetcode.com/problems/sqrtx/)       | [Python](./Python/sqrtx.py)      | _O(logn)_        | _O(1)_         | Medium         ||
74| [Search a 2D Matrix](https://oj.leetcode.com/problems/search-a-2d-matrix/) | [Python](./Python/search-a-2d-matrix.py) | _O(logm + logn)_ | _O(1)_ | Medium   ||
81| [Search in Rotated Sorted Array II](https://oj.leetcode.com/problems/search-in-rotated-sorted-array-ii/) | [Python](./Python/search-in-rotated-sorted-array-ii.py) | _O(logn)_ | _O(1)_   | Medium         ||
153| [Find Minimum in Rotated Sorted Array](https://oj.leetcode.com/problems/find-minimum-in-rotated-sorted-array/)         | [Python](./Python/find-minimum-in-rotated-sorted-array.py)       | _O(logn)_        | _O(1)_          | Medium         ||
154| [Find Minimum in Rotated Sorted Array II](https://oj.leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/)      | [Python](./Python/find-minimum-in-rotated-sorted-array-ii.py)       | _O(logn)_ ~ _O(n)_        | _O(1)_          | Hard         ||
162| [Find Peak Element](https://oj.leetcode.com/problems/find-peak-element/) | [Python](./Python/find-peak-element.py)        | _O(logn)_       | _O(1)_          | Medium         ||

--- 

##Breadth-First Search
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
102| [Binary Tree Level Order Traversal](https://oj.leetcode.com/problems/binary-tree-level-order-traversal/)| [Python](./Python/binary-tree-level-order-traversal.py)| _O(n)_| _O(n)_| Easy  || 
107| [Binary Tree Level Order Traversal II](https://oj.leetcode.com/problems/binary-tree-level-order-traversal-ii/)| [Python](./Python/binary-tree-level-order-traversal-ii.py) | _O(n)_| _O(n)_| Easy  ||
103| [Binary Tree Zigzag Level Order Traversal](https://oj.leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)| [Python](./Python/binary-tree-zigzag-level-order-traversal.py) | _O(n)_| _O(n)_| Medium  ||  
117| [Populating Next Right Pointers in Each Node II](https://oj.leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/)|[Python](./Python/populating-next-right-pointers-in-each-node-ii.py)| _O(n)_ | _O(1)_ | Hard ||
127| [Word Ladder](https://oj.leetcode.com/problems/word-ladder/)|[Python](./Python/word-ladder.py) | _O(n * d)_      | _O(d)_          | Medium         ||
130| [Surrounded Regions](https://oj.leetcode.com/problems/surrounded-regions/)|[Python](./Python/surrounded-regions.py)| _O(m * n)_ | _O(m + n)_ | Medium         ||
133| [Clone Graph](https://oj.leetcode.com/problems/clone-graph/)| [Python](./Python/clone-graph.py)   | _O(n)_          | _O(n)_          | Medium         ||
207| [Course Schedule](https://oj.leetcode.com/problems/course-schedule/)| [Python](./Python/course-schedule.py)   | _O(\|V\| + \|E\|)_          | _O(\|E\|)_          | Medium         ||
210| [Course Schedule II](https://oj.leetcode.com/problems/course-schedule-ii/)| [Python](./Python/course-schedule-ii.py)   | _O(\|V\| + \|E\|)_          | _O(\|E\|)_          | Medium         ||

--- 

##Depth-First Search
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
22| [Generate Parentheses](https://oj.leetcode.com/problems/generate-parentheses/)| [Python](./Python/generate-parentheses.py)| _O(4^n / n^(3/2))_ | _O(n)_   | Medium         ||
37| [Sudoku Solver](https://oj.leetcode.com/problems/sudoku-solver/) | [Python](./Python/sudoku-solver.py) | _O((9!)^9)_  | _O(1)_          | Hard           ||
39| [Combination Sum](https://oj.leetcode.com/problems/combination-sum/)| [Python](./Python/combination-sum.py) | _O(n^m)_    | _O(m)_          | Medium         ||
40| [Combination Sum II](https://oj.leetcode.com/problems/combination-sum-ii/)| [Python](./Python/combination-sum-ii.py)| _O(n! / m!(n-m)!)_| _O(m)_         | Medium         ||
51| [N-Queens](https://oj.leetcode.com/problems/n-queens/)      | [Python](./Python/n-queens.py)   | _O(n!)_         | _O(n)_          | Hard           ||
52| [N-Queens-II](https://oj.leetcode.com/problems/n-queens-ii/)   | [Python](./Python/n-queens-ii.py) | _O(n!)_        | _O(n)_          | Hard           ||
77| [Combinations](https://oj.leetcode.com/problems/combinations/)  | [Python](./Python/combinations.py) | _O(n!)_       | _O(n)_          | Medium         ||
79| [Word Search](https://oj.leetcode.com/problems/word-search/) | [Python](./Python/word-search.py) | _O(m * n * l)_ | _O(l)_  | Medium         ||
93| [Restore IP Addresses](https://oj.leetcode.com/problems/restore-ip-addresses/) | [Python](./Python/restore-ip-addresses.py) | _O(n^m)_ ~ _O(3^4)_ | _O(n * m)_ ~ _O(3 * 4)_ | Medium         ||
112| [Path Sum](https://oj.leetcode.com/problems/path-sum/)      | [Python](./Python/path-sum.py)   | _O(n)_          | _O(h)_          | Easy           ||
113| [Path Sum II](https://oj.leetcode.com/problems/path-sum-ii/)   | [Python](./Python/path-sum-ii.py) | _O(n)_         | _O(h)_          | Medium         ||
131| [Palindrome Partitioning](https://oj.leetcode.com/problems/palindrome-partitioning/) | [Python](./Python/palindrome-partitioning.py) | _O(n^2)_ ~ _O(2^n)_ | _O(n^2)_ | Medium ||
199| [Binary Tree Right Side View](https://oj.leetcode.com/problems/binary-tree-right-side-view/) | [Python](./Python/binary-tree-right-side-view.py) | _O(n)_     | _O(h)_ | Medium  ||
200| [Number of Islands](https://leetcode.com/problems/number-of-islands/) | [Python](./Python/number-of-islands.py) | _O(m * n)_ | _O(m * n)_| Medium         ||

--- 

##Dynamic Programming
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
10| [Regular Expression Matching](https://oj.leetcode.com/problems/regular-expression-matching/) | [Python](./Python/regular-expression-matching.py) | _O(m * n)_ | _O(n)_ | Hard ||
53| [Maximum Subarray](https://oj.leetcode.com/problems/maximum-subarray/)|[Python](./Python/maximum-subarray.py)| _O(n)_     | _O(1)_         | Medium         ||
62| [Unique Paths](https://oj.leetcode.com/problems/unique-paths/)    | [Python](./Python/unique-paths.py)| _O(m * n)_      | _O(m + n)_   | Medium         ||
63| [Unique Paths II](https://oj.leetcode.com/problems/unique-paths-ii/) | [Python](./Python/unique-paths-ii.py) |  _O(m * n)_ | _O(m + n)_   | Medium         ||
64| [Minimum Path Sum](https://oj.leetcode.com/problems/minimum-path-sum/)|[Python](./Python/minimum-path-sum.py)| _O(m * n)_ | _O(m + n)_     | Medium         ||
70| [Climbing Stairs](https://oj.leetcode.com/problems/climbing-stairs/)| [Python](./Python/climbing-stairs.py) | _O(n)_    | _O(1)_          | Easy           ||
72| [Edit Distance](https://oj.leetcode.com/problems/edit-distance/)|[Python](./Python/edit-distance.py)| _O(m * n)_      | _O(m + n)_      | Hard           ||
85| [Maximal Rectangle](https://oj.leetcode.com/problems/maximal-rectangle/)|[Python](./Python/maximal-rectangle.py)| _O(n^2)_ | _O(n)_         | Hard           ||
87| [Scramble String](https://oj.leetcode.com/problems/scramble-string/) | [Python](./Python/scramble-string.py) | _O(n^4)_ | _O(n^3)_        | Hard           ||
91| [Decode Ways](https://oj.leetcode.com/problems/decode-ways/)   | [Python](./Python/decode-ways.py)| _O(n)_          | _O(1)_          | Medium         ||
96| [Unique Binary Search Trees](https://oj.leetcode.com/problems/unique-binary-search-trees/) | [Python](./Python/unique-binary-search-trees.py) | _O(n^2)_      | _O(n)_         | Medium         ||
97| [Interleaving String](https://oj.leetcode.com/problems/interleaving-string/)|[Python](./Python/interleaving-string.py)| _O(m * n)_ | _O(m + n)_ | Hard         ||
115| [Distinct Subsequences](https://oj.leetcode.com/problems/distinct-subsequences/)|[Python](./Python/distinct-subsequences.py)| _O(n^2)_ | _O(n)_ | Hard           ||
120| [Triangle](https://oj.leetcode.com/problems/triangle/)       | [Python](./Python/triangle.py)   | _O(m * n)_      | _O(n)_         | Medium         ||
123| [Best Time to Buy and Sell Stock III](https://oj.leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/) | [Python](./Python/best-time-to-buy-and-sell-stock-iii.py) | _O(n)_ | _O(1)_ | Hard ||
132| [Palindrome Partitioning II](https://oj.leetcode.com/problems/palindrome-partitioning-ii/) | [Python](./Python/palindrome-partitioning-ii.py) | _O(n^2)_ | _O(n^2)_ | Hard ||
139| [Word Break](https://oj.leetcode.com/problems/word-break/)     | [Python](./Python/word-break.py) |  _O(n^2)_         | _O(n)_       | Medium         ||
140| [Word Break II](https://oj.leetcode.com/problems/word-break-ii/)  | [Python](./Python/word-break-ii.py) |  _O(n^2)_      | _O(n)_       | Hard           ||
152| [Maximum Product Subarray](https://oj.leetcode.com/problems/maximum-product-subarray/)|[Python](./Python/maximum-product-subarray.py)| _O(n)_ | _O(1)_ | Medium     ||
174| [Dungeon Game](https://oj.leetcode.com/problems/dungeon-game/)  | [Python](./Python/dungeon-game.py)| _O(m * n)_     | _O(m + n)_      | Hard           ||
188| [Best Time to Buy and Sell Stock IV](https://oj.leetcode.com/problems/best-time-to-buy-and-sell-stock-iv/)| [Python](./Python/best-time-to-buy-and-sell-stock-iv.py) | _O(k * n)_ | _O(k)_ | Hard ||
198| [House Robber](https://oj.leetcode.com/problems/house-robber/)| [Python](./Python/house-robber.py) | _O(n)_          | _O(1)_          | Easy           ||
213| [House Robber II](https://oj.leetcode.com/problems/house-robber-ii/)| [C++](./C++/house-robber-ii.cpp) [Python](./Python/house-robber-ii.py) | _O(n)_          | _O(1)_          | Medium           ||

--- 

##Backtracking
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
126| [Word Ladder II](https://oj.leetcode.com/problems/word-ladder-ii/)   |[Python](./Python/word-ladder-ii.py) | _O(n * d)_ | _O(d)_         | Hard         ||

--- 

##Greedy
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
11| [Container With Most Water](https://oj.leetcode.com/problems/container-with-most-water/)| [Python](./Python/container-with-most-water.py) | _O(n)_ | _O(1)_ | Medium ||
42| [Trapping Rain Water](https://oj.leetcode.com/problems/trapping-rain-water/) | [Python](./Python/trapping-rain-water.py) | _O(n)_ | _O(1)_ | Hard || Tricky
44| [Wildcard Matching](https://oj.leetcode.com/problems/wildcard-matching/) | [Python](./Python/wildcard-matching.py) | _O(m + n)_ | _O(1)_    | Hard           || Tricky
45| [Jump Game II](https://oj.leetcode.com/problems/jump-game-ii/)  | [Python](./Python/jump-game-ii.py) | _O(n)_        | _O(1)_          | Hard           ||
55| [Jump Game](https://oj.leetcode.com/problems/jump-game/)     | [Python](./Python/jump-game.py)  | _O(n)_          | _O(1)_          | Medium         ||
84| [Largest Rectangle in Histogram](https://oj.leetcode.com/problems/largest-rectangle-in-histogram/) | [Python](./Python/largest-rectangle-in-histogram.py) | _O(n)_ | _O(n)_ | Hard || Tricky
122| [Best Time to Buy and Sell Stock II](https://oj.leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/)| [Python](./Python/best-time-to-buy-and-sell-stock-ii.py) | _O(n)_ | _O(1)_ | Medium ||
134| [Gas Station](https://oj.leetcode.com/problems/gas-station/)| [Python](./Python/gas-station.py)   | _O(n)_          | _O(1)_          | Medium         ||
135| [Candy](https://oj.leetcode.com/problems/candy/)| [Python](./Python/candy.py) | _O(n)_ | _O(n)_ | Hard ||

---

##SQL
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
175| [Combine Two Tables](https://oj.leetcode.com/problems/combine-two-tables/) | [MySQL](./MySQL/combine-two-tables.sql) | _O(m + n)_   | _O(m + n)_ | Easy     ||
176| [Second Highest Salary](https://oj.leetcode.com/problems/second-highest-salary/) | [MySQL](./MySQL/second-highest-salary.sql) | _O(n)_ | _O(1)_ | Easy         ||
177| [Nth Highest Salary](https://oj.leetcode.com/problems/nth-highest-salary/) | [MySQL](./MySQL/nth-highest-salary.sql) | _O(n^2)_   | _O(n)_ | Medium         ||
178| [Rank Scores](https://oj.leetcode.com/problems/rank-scores/) | [MySQL](./MySQL/rank-scores.sql) | _O(n^2)_        | _O(n)_          | Medium         ||
180| [Consecutive Numbers](https://oj.leetcode.com/problems/consecutive-numbers/) | [MySQL](./MySQL/consecutive-numbers.sql) | _O(n)_   | _O(n)_ | Medium         ||
181| [Employees Earning More Than Their Managers](https://oj.leetcode.com/problems/employees-earning-more-than-their-managers/) | [MySQL](./MySQL/employees-earning-more-than-their-managers.sql) | _O(n^2)_   | _O(1)_ | Easy     ||
182| [Duplicate Emails](https://oj.leetcode.com/problems/duplicate-emails/) | [MySQL](./MySQL/duplicate-emails.sql) | _O(n^2)_ | _O(n)_       | Easy           ||
183| [Customers Who Never Order](https://oj.leetcode.com/problems/customers-who-never-order/) | [MySQL](./MySQL/customers-who-never-order.sql) | _O(n^2)_ | _O(1)_       | Easy           ||
184| [Department Highest Salary](https://oj.leetcode.com/problems/department-highest-salary/) | [MySQL](./MySQL/department-highest-salary.sql) | _O(n^2)_   | _O(n)_ | Medium         ||
185| [Department Top Three Salaries](https://oj.leetcode.com/problems/department-top-three-salaries/) | [MySQL](./MySQL/department-top-three-salaries.sql) | _O(n^2)_   | _O(n)_ | Hard         ||
196| [Delete Duplicate Emails](https://oj.leetcode.com/problems/delete-duplicate-emails/) | [MySQL](./MySQL/delete-duplicate-emails.sql) | _O(n^2)_ | _O(n)_       | Easy           ||
197| [Rising Temperature](https://oj.leetcode.com/problems/rising-temperature/) | [MySQL](./MySQL/rising-temperature.sql) | _O(n^2)_ | _O(n)_       | Easy           ||

---

##Shell Script
  #  | Problem         |  Solution       |  Time           | Space           | Difficulty    | Tag          | Notes
-----|---------------- | --------------- | --------------- | --------------- | ------------- |--------------| -----
192 | [Word Frequency](https://oj.leetcode.com/problems/word-frequency/) | [Shell](./Shell/word-frequency.sh) | _O(n)_     | _O(k)_          | Medium         ||
193 | [Valid Phone Numbers](https://oj.leetcode.com/problems/valid-phone-numbers/) | [Shell](./Shell/valid-phone-numbers.sh) | _O(n)_ | _O(1)_    | Easy           ||
194 | [Transpose File](https://oj.leetcode.com/problems/transpose-file/) | [Shell](./Shell/transpose-file.sh) | _O(n^2)_   | _O(n^2)_        | Medium         ||
195 | [Tenth Line](https://oj.leetcode.com/problems/tenth-line/) | [Shell](./Shell/tenth-line.sh)    | _O(n)_          | _O(1)_          | Easy           ||
