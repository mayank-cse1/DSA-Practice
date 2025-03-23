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

Let me know which algorithms you'd like to explore further! 🚀
These algorithms cover the most important topics under DSA. 
