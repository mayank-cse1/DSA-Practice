# DSA-Practice

Here’s a concise explanation of each algorithm across different DSA topics:

---

### **Sorting Algorithms**
| **Algorithm**          | **Explanation**                                                                                              |
|-------------------------|------------------------------------------------------------------------------------------------------------|
| **Bubble Sort**         | Repeatedly compares adjacent elements and swaps them if they are in the wrong order.                       |
| **Insertion Sort**      | Builds a sorted array one element at a time by placing each element in its correct position.               |
| **Selection Sort**      | Selects the smallest (or largest) element and swaps it with the first unsorted element.                    |
| **Merge Sort**          | Divides the array into halves, sorts each half, and then merges them.                                      |
| **Quick Sort**          | Picks a pivot, partitions the array into smaller/greater values, and recursively sorts the partitions.     |
| **Heap Sort**           | Uses a heap to repeatedly extract the maximum or minimum element to sort the array.                        |
| **Counting Sort**       | Counts occurrences of each value and builds the sorted array from these counts (non-comparison based).    |
| **Radix Sort**          | Sorts numbers by processing digits one at a time, starting from the least significant digit.              |

---

### **Search Algorithms**
| **Algorithm**          | **Explanation**                                                                                              |
|-------------------------|------------------------------------------------------------------------------------------------------------|
| **Linear Search**       | Sequentially checks each element until the desired one is found.                                           |
| **Binary Search**       | Efficiently searches in a sorted array by repeatedly dividing the search range by half.                    |
| **Exponential Search**  | Finds a range where the target may exist and uses binary search within that range.                         |

---

### **Graph Algorithms**
| **Algorithm**          | **Explanation**                                                                                              |
|-------------------------|------------------------------------------------------------------------------------------------------------|
| **BFS (Breadth-First)** | Explores all neighbors at the current level before moving deeper (used for shortest paths in unweighted graphs). |
| **DFS (Depth-First)**   | Explores as far as possible down each branch before backtracking (used for connected components, cycles).   |
| **Dijkstra's Algorithm**| Finds shortest paths from a single source to all other nodes in weighted graphs.                           |
| **Bellman-Ford**        | Handles shortest paths but works even with negative-weight edges.                                           |
| **Floyd-Warshall**      | Computes shortest paths between all pairs of nodes.                                                        |
| **Prim's Algorithm**    | Finds the Minimum Spanning Tree (MST) by adding edges with the smallest weight.                            |
| **Kruskal's Algorithm** | Finds the MST by sorting edges and adding them while avoiding cycles.                                      |
| **Topological Sort**    | Orders vertices of a Directed Acyclic Graph (DAG) such that all edges point forward.                       |
| **Tarjan's Algorithm**  | Finds Strongly Connected Components (SCCs) in a directed graph using DFS.                                  |
| **Kosaraju's Algorithm**| Another approach to find SCCs, using two passes of DFS.                                                   |

---

### **Greedy Algorithms**
| **Algorithm**               | **Explanation**                                                                                          |
|------------------------------|--------------------------------------------------------------------------------------------------------|
| **Activity Selection**       | Selects the maximum number of non-overlapping activities based on end times.                          |
| **Huffman Coding**           | Builds an optimal prefix code tree for data compression.                                              |
| **Fractional Knapsack**      | Maximizes total value by taking fractions of items, sorted by value/weight ratio.                     |

---

### **Dynamic Programming (DP)**
| **Algorithm**              | **Explanation**                                                                                          |
|-----------------------------|---------------------------------------------------------------------------------------------------------|
| **LCS**                    | Finds the longest subsequence common to two strings.                                                   |
| **LIS**                    | Finds the longest subsequence with increasing order.                                                   |
| **0/1 Knapsack**           | Maximizes value with a weight constraint, where items cannot be divided.                               |
| **Matrix Chain Multiplication** | Optimizes parenthesization to minimize the cost of multiplying matrices.                          |
| **Coin Change Problem**    | Finds the minimum number of coins needed for a target sum.                                             |
| **Rod Cutting Problem**    | Cuts rods into pieces to maximize revenue.                                                             |

---

### **Divide and Conquer**
| **Algorithm**            | **Explanation**                                                                                          |
|---------------------------|---------------------------------------------------------------------------------------------------------|
| **Merge Sort**            | Splits the array, sorts each half, and merges them.                                                    |
| **Quick Sort**            | Partitions array and recursively sorts around a pivot.                                                 |
| **Binary Search**         | Repeatedly divides the search range in half on sorted arrays.                                          |
| **Maximum Subarray (Kadane's Algorithm)** | Finds the contiguous subarray with the maximum sum in linear time.                      |

---

### **Backtracking**
| **Algorithm**              | **Explanation**                                                                                          |
|-----------------------------|---------------------------------------------------------------------------------------------------------|
| **N-Queens**               | Places queens on a chessboard such that no two queens attack each other.                               |
| **Sudoku Solver**          | Solves a Sudoku puzzle by filling in cells using backtracking.                                         |
| **Subset Sum**             | Checks if any subset of numbers sums to a target.                                                     |
| **Permutations/Combinations** | Generates all possible arrangements or combinations of elements.                                    |

---

### **String Algorithms**
| **Algorithm**               | **Explanation**                                                                                          |
|------------------------------|---------------------------------------------------------------------------------------------------------|
| **KMP Algorithm**            | Searches for a pattern in a string using partial match information.                                   |
| **Rabin-Karp Algorithm**     | Uses a rolling hash to efficiently find substrings.                                                   |
| **Z-Algorithm**              | Finds occurrences of a pattern by computing Z-values of the string.                                   |
| **Trie**                     | Stores strings for efficient prefix-based operations.                                                 |
| **Suffix Arrays**            | Builds an array to find substrings and patterns efficiently.                                          |
| **Longest Palindromic Substring** | Finds the longest palindromic substring in a string.                                               |

---

### **Tree Algorithms**
| **Algorithm**                  | **Explanation**                                                                                      |
|---------------------------------|-----------------------------------------------------------------------------------------------------|
| **Tree Traversals**            | Inorder, Preorder, and Postorder traverse nodes of a tree in specific orders.                      |
| **Breadth-First Traversal**    | Visits nodes level by level.                                                                       |
| **Lowest Common Ancestor (LCA)** | Finds the lowest common ancestor of two nodes in a tree.                                           |
| **Segment Trees**              | Supports efficient range queries and updates on an array.                                          |
| **Fenwick Tree (BIT)**         | Efficiently computes prefix sums and updates in logarithmic time.                                  |

---

### **Mathematical Algorithms**
| **Algorithm**             | **Explanation**                                                                                          |
|----------------------------|---------------------------------------------------------------------------------------------------------|
| **Sieve of Eratosthenes**  | Efficiently generates prime numbers up to a given number.                                              |
| **Euclidean Algorithm**    | Computes the Greatest Common Divisor (GCD) of two numbers.                                             |
| **Fast Exponentiation**    | Computes powers of numbers in logarithmic time.                                                        |
| **Modular Arithmetic**     | Performs arithmetic under a modulo to handle large numbers.                                           |

---

Sure Mayank! Let's break down each **"sub"** term from the table you shared with a **simple explanation and example**. 🚀  
This will help you understand their difference in practical coding scenarios.

---
# Confusing Terms

## 🔹 Array / String Based

---

### **Subarray**
- *Definition*: A **contiguous** part of an array.
- *Example*:
```python
arr = [1, 2, 3]
Possible subarrays: [1], [2], [3], [1,2], [2,3], [1,2,3]
```
-  Used in: **Kadane’s Algorithm** (max subarray sum)
- **Key Questions**:
  1. [LeetCode 53 - Maximum Subarray (Kadane's Algorithm)](https://leetcode.com/problems/maximum-subarray/)
  2. [LeetCode 560 - Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
  3. [LeetCode 974 - Subarray Sums Divisible by K](https://leetcode.com/problems/subarray-sums-divisible-by-k/)
  4. [LeetCode 325 - Maximum Size Subarray Sum Equals k](https://leetcode.com/problems/maximum-size-subarray-sum-equals-k/)
  5. [GFG - Largest subarray with 0 sum](https://practice.geeksforgeeks.org/problems/largest-subarray-with-0-sum/1)

---

### **Subsequence**
- *Definition*: Elements in the **same order**, but **not necessarily contiguous**.
- *Example*:
```python
arr = [1, 2, 3]
Possible subsequences: [], [1], [2], [3], [1,2], [1,3], [2,3], [1,2,3]
```
-  Used in: **Longest Common Subsequence (LCS)**
- **Key Questions**:
  1. [LeetCode 300 - Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
  2. [LeetCode 1143 - Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
  3. [LeetCode 392 - Is Subsequence](https://leetcode.com/problems/is-subsequence/)
  4. [GFG - Number of Subsequences That Satisfy the Given Sum Condition](https://practice.geeksforgeeks.org/problems/subsequences-that-satisfy-the-given-sum-condition/1)

---

### **Subset**
- *Definition*: Any combination of elements, **order doesn’t matter**, and can be **any length**.
- *Example*:
```python
arr = [1, 2]
Subsets: [], [1], [2], [1, 2]
```
-  Used in: **Subset Sum**, **Power Set**, **Backtracking problems**
- **Key Questions**:
  1. [LeetCode 78 - Subsets (Power Set)](https://leetcode.com/problems/subsets/)
  2. [LeetCode 90 - Subsets II (With Duplicates)](https://leetcode.com/problems/subsets-ii/)
  3. [LeetCode 416 - Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
  4. [LeetCode 494 - Target Sum](https://leetcode.com/problems/target-sum/)
  5. [LeetCode 1049 - Last Stone Weight II (Subset Diff)](https://leetcode.com/problems/last-stone-weight-ii/)

---

### **Substring**
- *Definition*: A **contiguous** part of a **string**.
- *Example*:
```python
s = "abc"
Substrings: "a", "b", "c", "ab", "bc", "abc"
```
- Used in: **Palindrome problems**, **String pattern matching**
- **Key Questions**:
  1. [LeetCode 5 - Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
  2. [LeetCode 3 - Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
  3. [LeetCode 76 - Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
  4. [LeetCode 438 - Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
  5. [LeetCode 30 - Substring with Concatenation of All Words](https://leetcode.com/problems/substring-with-concatenation-of-all-words/)

---

### **Submatrix**
-  *Definition*: A rectangular region within a matrix.
-  *Example*:
```python
Matrix = [[1, 2],
          [3, 4]]
Possible submatrices:
- [[1]], [[2]], [[3]], [[4]]
- [[1,2]], [[3,4]]
- [[1], [3]], [[2], [4]]
- [[1,2],[3,4]]
```
-  Used in: **Max sum submatrix**, **prefix sum** on 2D arrays
- **Key Questions**:
  1. [LeetCode 85 - Maximal Rectangle](https://leetcode.com/problems/maximal-rectangle/)
  2. [LeetCode 363 - Max Sum of Rectangle No Larger Than K](https://leetcode.com/problems/max-sum-of-rectangle-no-larger-than-k/)
  3. [LeetCode 221 - Maximal Square](https://leetcode.com/problems/maximal-square/)
  4. [GFG - Maximum sum submatrix](https://practice.geeksforgeeks.org/problems/maximum-sum-rectangle/1)

---

### **Subsegment**
-  *Definition*: Often used like a subarray, especially in **competitive programming**.
-  *Example*: Same as subarray: a contiguous segment like `[2, 3, 5]` from `[1, 2, 3, 5, 6]`
- **Key Questions**:
  1. [Codeforces 978D - Almost Arithmetic Progression](https://codeforces.com/contest/978/problem/D)
  2. [Codeforces 978C - Push Pull](https://codeforces.com/contest/978/problem/C)
  3. [Codeforces 660C - Hard Process (Max 1s in subsegment with at most k 0s)](https://codeforces.com/problemset/problem/660/C)

---

##  Tree / Graph Based

---

###  **Subtree**
-  *Definition*: A node and all its descendants in a tree.
-  *Example*:

```text
Tree:
       1
      / \
     2   3
    / \
   4   5

Subtree rooted at 2:
     2
    / \
   4   5
```
-  Used in: **Check subtree**, **LCA**, **Postorder DFS**
- **Key Questions**:
  1. [LeetCode 572 - Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/)
  2. [LeetCode 865 - Smallest Subtree with All the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/)
  3. [LeetCode 236 - Lowest Common Ancestor of Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
  4. [GFG - Largest subtree sum in a tree](https://practice.geeksforgeeks.org/problems/largest-subtree-sum-in-a-tree/1)

---

###  **Subgraph**
-  *Definition*: A portion of a graph (some nodes & edges).
-  *Example*:
```text
Graph:
A -- B -- C -- D

A subgraph might be: A -- B
```
- 🛠️ Used in: **Connected components**, **Spanning Trees**
- **Key Questions**:
  1. [LeetCode 323 - Number of Connected Components in an Undirected Graph](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)
  2. [LeetCode 1135 - Connecting Cities With Minimum Cost](https://leetcode.com/problems/connecting-cities-with-minimum-cost/)
  3. [GFG - Detect cycle in undirected graph](https://practice.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/1)
---

##  DP and Optimization

---

###  **Subset Sum Problem**
-  *Definition*: Is there a subset of elements whose sum equals a target?
-  *Example*:
```python
arr = [3, 34, 4, 12, 5, 2], target = 9
Subset [4, 5] gives sum 9 → ✅
```
- 🛠️ Solved using: **Dynamic Programming / Backtracking**
- **Key Questions**:
  1. [LeetCode 416 - Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
  2. [LeetCode 494 - Target Sum](https://leetcode.com/problems/target-sum/)
  3. [GFG - Subset Sum Problem](https://practice.geeksforgeeks.org/problems/subset-sum-problem2014/1)

---

###  **Subproblem**
-  *Definition*: Breaking a problem into smaller repeatable problems.
-  *Example*:
```python
Fibonacci(n) = Fibonacci(n-1) + Fibonacci(n-2)
Here, Fibonacci(n-1) is a subproblem.
```
-  Used in: **Memoization**, **Tabulation (DP)**

- **Key Questions**:
  1. [LeetCode 70 - Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
  2. [LeetCode 198 - House Robber](https://leetcode.com/problems/house-robber/)
  3. [LeetCode 322 - Coin Change](https://leetcode.com/problems/coin-change/)

---

##  Other Algorithm Terms

---

### **Submodular Function**
-  *Definition*: A function with a **diminishing returns** property.
-  *Example*:
- Suppose you're selecting items for a bag. Adding item A gives value 10.
- If your bag is empty → A gives +10.
- But if your bag already has items, A gives less than +10.

 Used in optimization (e.g., **greedy algorithms** for coverage problems).
- **Key Questions**:
  1. **Maximum Coverage Problem** (used in system design, Google interviews)
  2. [Stanford Submodularity Lecture](https://web.stanford.edu/class/cs224w/slides/14-submodularity.pdf)
  3. **Sensor Placement Problem** (Set optimization under submodular constraints)

---

### **Sublinear Time**
-  *Definition*: Algorithm that runs in less than O(n) time.
-  *Example*:
```python
arr = [1, 2, 3, 4, 5]
Search for 3 using Binary Search → O(log n) time ✅ (sublinear)
```
-  Used in: **Searching in sorted data**, **Hashing**, **Indexing**
- **Key Questions**:
  1. [LeetCode 162 - Find Peak Element](https://leetcode.com/problems/find-peak-element/)
  2. [LeetCode 704 - Binary Search](https://leetcode.com/problems/binary-search/)
  3. [LeetCode 33 - Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)

---

## ✅ Summary Table (with Examples)

| Term           | Key Idea                     | Example                                      |
|----------------|------------------------------|----------------------------------------------|
| Subarray       | Contiguous part of array     | [1,2] from [1,2,3]                            |
| Subsequence    | Ordered but not contiguous   | [1,3] from [1,2,3]                            |
| Subset         | Any combination              | [1,3] or [] from [1,2,3]                      |
| Substring      | Contiguous part of string    | "ab" from "abc"                              |
| Submatrix      | Rectangular matrix section   | [[1,2],[3,4]]                                 |
| Subsegment     | Contiguous part (CP term)    | [2,3] from [1,2,3,4]                          |
| Subtree        | Node + all descendants       | Subtree rooted at 2                          |
| Subgraph       | Portion of a graph           | A-B in A-B-C                                 |
| Subset Sum     | Subset adding to a target    | [4,5] → sum = 9                              |
| Subproblem     | Smaller part of problem      | Fibonacci(n-1)                               |
| Submodular     | Diminishing returns          | Adding new feature has less gain             |
| Sublinear Time | Faster than O(n)             | Binary search → O(log n)                     |

---



Always happy to help you level up 💪
