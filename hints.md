| Common Algorithms / Data Structures | Problem Signal / Clue                            | Usually Means                 | Typical Time Complexity  | Classic Examples                               |
| ----------------------------------- | ------------------------------------------------ | ----------------------------- | ------------------------ | ---------------------------------------------- |
| Backtracking                        | Generate all combinations                        | Explore all possibilities     | Exponential              | Permutations, N-Queens                         |
| Backtracking, Bitmasking            | Constraints: `n <= 20`                           | Exponential acceptable        | O(2^n)                   | Subsets                                        |
| BFS                                 | Shortest path in unweighted graph                | Level-by-level exploration    | O(V + E)                 | Word Ladder                                    |
| BFS                                 | “Fewest moves/steps”                             | Minimum distance search       | O(V + E)                 | Open the Lock                                  |
| Binary Search                       | “Search in rotated sorted array”                 | Modified ordering logic       | O(log n)                 | Rotated Array Search                           |
| Binary Search, Two Pointers         | Array is **sorted**                              | Exploit ordering              | O(log n), O(n)           | Search Insert Position, First/Last Occurrence  |
| Binary Search + Feasibility Check   | “Minimum possible maximum” / “Can we achieve X?” | Binary Search on Answer       | O(n log n)               | Koko Eating Bananas                            |
| DFS, BFS                            | Grid / island traversal                          | Treat grid as graph           | O(m × n)                 | Number of Islands                              |
| DFS, BFS                            | Tree hierarchy / levels                          | Traversal                     | O(n)                     | Level Order Traversal                          |
| DFS + Backtracking                  | “All paths”                                      | Explore every route           | Exponential              | Path Sum II                                    |
| Dijkstra                            | Weighted shortest path                           | Relax edges                   | O(E log V)               | Network Delay Time                             |
| DP                                  | Decision depends on previous states              | State transitions             | Varies                   | House Robber                                   |
| DP, Graph                           | Constraints: `n <= 10^3`                         | Quadratic may work            | O(n²)                    | LIS DP                                         |
| Dynamic Programming                 | “Maximum/minimum ways” with overlapping work     | Reuse subproblems             | Usually O(n²) or O(n)    | Coin Change                                    |
| Floyd’s Cycle Detection             | Detect cycles in linked list                     | Fast vs slow movement         | O(n)                     | Linked List Cycle                              |
| Greedy                              | “Choose non-overlapping intervals”               | Sort by end time              | O(n log n)               | Activity Selection                             |
| Greedy                              | Schedule / meeting optimization                  | Local optimal decisions       | O(n log n)               | Meeting Rooms                                  |
| Greedy / BFS / DP                   | “Can reach destination?”                         | State traversal               | Varies                   | Jump Game                                      |
| Greedy + Sorting                    | Interval overlap / merge                         | Sort then process             | O(n log n)               | Merge Intervals                                |
| Hashing, Heap, Binary Search        | Constraints: `n <= 10^5`                         | Need efficient solution       | O(n log n) or O(n)       | Most interview optimal solutions               |
| HashMap                             | Find duplicates / frequency                      | Counting                      | O(n)                     | Valid Anagram, Top K Frequent                  |
| HashMap, HashSet                    | Need fast lookup / existence check               | Constant-time lookup          | O(1) average             | Two Sum, Contains Duplicate                    |
| Heap                                | Merge multiple sorted lists                      | Efficient repeated minimum    | O(n log k)               | Merge K Sorted Lists                           |
| Heap, QuickSelect                   | “kth smallest/largest”                           | Partial ordering              | O(n log k) / O(n) avg    | Kth Largest Element                            |
| Heap, QuickSelect                   | “Top K”                                          | Partial sorting               | O(n log k)               | Top K Frequent Elements                        |
| Heap / Priority Queue               | Need current min/max repeatedly                  | Efficient priority retrieval  | O(log n)                 | Kth Largest Element                            |
| KMP, Rabin-Karp                     | Pattern matching in strings                      | Efficient substring search    | O(n)                     | strStr()                                       |
| Lower Bound / Upper Bound           | “Find first/last occurrence”                     | Boundary search               | O(log n)                 | Search Range                                   |
| Memoization                         | “Repeated calculations”                          | Cache results                 | Reduced from exponential | Fibonacci DP                                   |
| Monotonic Stack                     | Histogram / span problems                        | Stack-based boundary tracking | O(n)                     | Largest Rectangle in Histogram                 |
| Monotonic Stack                     | “Next greater/smaller”                           | Maintain monotonic order      | O(n)                     | Daily Temperatures                             |
| Prefix Sum                          | Many range sum queries                           | Preprocessing                 | O(1) query               | Range Sum Query                                |
| Recursion, Divide & Conquer         | Recursive structure                              | Divide into subproblems       | O(n log n) typically     | Merge Sort                                     |
| Segment Tree, Fenwick Tree          | Range updates + queries                          | Efficient segment operations  | O(log n)                 | Mutable Range Sum                              |
| Sliding Window                      | Contiguous subarray / substring                  | Window processing             | O(n)                     | Longest Substring Without Repeating Characters |
| Sliding Window                      | Fixed-size window                                | Rolling computation           | O(n)                     | Max Sum Subarray of Size K                     |
| Sliding Window + HashMap            | “Exactly K distinct”                             | Controlled window             | O(n)                     | Subarrays with K Different Integers            |
| Sorting + Greedy                    | Need lexicographically smallest/largest          | Ordered greedy choice         | O(n log n)               | Reorganize String                              |
| Stack                               | “Expression evaluation”                          | Operator precedence handling  | O(n)                     | Basic Calculator                               |
| Stack                               | “Parentheses validation”                         | Nested structure tracking     | O(n)                     | Valid Parentheses                              |
| Topological Sort                    | Dependencies / prerequisites                     | Ordering constraints          | O(V + E)                 | Course Schedule                                |
| Trie                                | Prefix search / autocomplete                     | Character tree                | O(length of word)        | Implement Trie                                 |
| Two Heaps                           | Streaming median                                 | Dynamic balancing             | O(log n)                 | Find Median from Data Stream                   |
| Two Pointers                        | “Closest pair”, “Remove duplicates”              | Linear pointer movement       | O(n)                     | Remove Duplicates from Sorted Array            |
| Two Pointers                        | Pair in sorted array                             | Shrink/expand pointers        | O(n)                     | Two Sum II                                     |
| Two Pointers, Swapping              | “Without extra space”                            | In-place optimization         | O(1) space               | Reverse Array                                  |
| Union Find (DSU)                    | Connectivity / grouping                          | Merge sets efficiently        | Near O(1)                | Number of Provinces                            |
