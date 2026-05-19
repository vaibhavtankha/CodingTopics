| Problem Signal / Clue                            | Usually Means                 | Common Algorithms / Data Structures | Typical Time Complexity  | Classic Examples                               |
| ------------------------------------------------ | ----------------------------- | ----------------------------------- | ------------------------ | ---------------------------------------------- |
| Array is **sorted**                              | Exploit ordering              | Binary Search, Two Pointers         | O(log n), O(n)           | Search Insert Position, First/Last Occurrence  |
| “Find first/last occurrence”                     | Boundary search               | Lower Bound / Upper Bound           | O(log n)                 | Search Range                                   |
| “Minimum possible maximum” / “Can we achieve X?” | Binary Search on Answer       | Binary Search + Feasibility Check   | O(n log n)               | Koko Eating Bananas                            |
| Need fast lookup / existence check               | Constant-time lookup          | HashMap, HashSet                    | O(1) average             | Two Sum, Contains Duplicate                    |
| Find duplicates / frequency                      | Counting                      | HashMap                             | O(n)                     | Valid Anagram, Top K Frequent                  |
| Contiguous subarray / substring                  | Window processing             | Sliding Window                      | O(n)                     | Longest Substring Without Repeating Characters |
| Fixed-size window                                | Rolling computation           | Sliding Window                      | O(n)                     | Max Sum Subarray of Size K                     |
| Pair in sorted array                             | Shrink/expand pointers        | Two Pointers                        | O(n)                     | Two Sum II                                     |
| “Closest pair”, “Remove duplicates”              | Linear pointer movement       | Two Pointers                        | O(n)                     | Remove Duplicates from Sorted Array            |
| “Next greater/smaller”                           | Maintain monotonic order      | Monotonic Stack                     | O(n)                     | Daily Temperatures                             |
| Histogram / span problems                        | Stack-based boundary tracking | Monotonic Stack                     | O(n)                     | Largest Rectangle in Histogram                 |
| Need current min/max repeatedly                  | Efficient priority retrieval  | Heap / Priority Queue               | O(log n)                 | Kth Largest Element                            |
| “Top K”                                          | Partial sorting               | Heap, QuickSelect                   | O(n log k)               | Top K Frequent Elements                        |
| Streaming median                                 | Dynamic balancing             | Two Heaps                           | O(log n)                 | Find Median from Data Stream                   |
| Tree hierarchy / levels                          | Traversal                     | DFS, BFS                            | O(n)                     | Level Order Traversal                          |
| Shortest path in unweighted graph                | Level-by-level exploration    | BFS                                 | O(V + E)                 | Word Ladder                                    |
| Weighted shortest path                           | Relax edges                   | Dijkstra                            | O(E log V)               | Network Delay Time                             |
| Dependencies / prerequisites                     | Ordering constraints          | Topological Sort                    | O(V + E)                 | Course Schedule                                |
| Generate all combinations                        | Explore all possibilities     | Backtracking                        | Exponential              | Permutations, N-Queens                         |
| “Maximum/minimum ways” with overlapping work     | Reuse subproblems             | Dynamic Programming                 | Usually O(n²) or O(n)    | Coin Change                                    |
| Decision depends on previous states              | State transitions             | DP                                  | Varies                   | House Robber                                   |
| Interval overlap / merge                         | Sort then process             | Greedy + Sorting                    | O(n log n)               | Merge Intervals                                |
| Schedule / meeting optimization                  | Local optimal decisions       | Greedy                              | O(n log n)               | Meeting Rooms                                  |
| Prefix search / autocomplete                     | Character tree                | Trie                                | O(length of word)        | Implement Trie                                 |
| Many range sum queries                           | Preprocessing                 | Prefix Sum                          | O(1) query               | Range Sum Query                                |
| Range updates + queries                          | Efficient segment operations  | Segment Tree, Fenwick Tree          | O(log n)                 | Mutable Range Sum                              |
| Detect cycles in linked list                     | Fast vs slow movement         | Floyd’s Cycle Detection             | O(n)                     | Linked List Cycle                              |
| Connectivity / grouping                          | Merge sets efficiently        | Union Find (DSU)                    | Near O(1)                | Number of Provinces                            |
| Grid / island traversal                          | Treat grid as graph           | DFS, BFS                            | O(m × n)                 | Number of Islands                              |
| Pattern matching in strings                      | Efficient substring search    | KMP, Rabin-Karp                     | O(n)                     | strStr()                                       |
| Recursive structure                              | Divide into subproblems       | Recursion, Divide & Conquer         | O(n log n) typically     | Merge Sort                                     |
| Need lexicographically smallest/largest          | Ordered greedy choice         | Sorting + Greedy                    | O(n log n)               | Reorganize String                              |
| Constraints: `n <= 20`                           | Exponential acceptable        | Backtracking, Bitmasking            | O(2^n)                   | Subsets                                        |
| Constraints: `n <= 10^3`                         | Quadratic may work            | DP, Graph                           | O(n²)                    | LIS DP                                         |
| Constraints: `n <= 10^5`                         | Need efficient solution       | Hashing, Heap, Binary Search        | O(n log n) or O(n)       | Most interview optimal solutions               |
| “Without extra space”                            | In-place optimization         | Two Pointers, Swapping              | O(1) space               | Reverse Array                                  |
| “Fewest moves/steps”                             | Minimum distance search       | BFS                                 | O(V + E)                 | Open the Lock                                  |
| “All paths”                                      | Explore every route           | DFS + Backtracking                  | Exponential              | Path Sum II                                    |
| “Exactly K distinct”                             | Controlled window             | Sliding Window + HashMap            | O(n)                     | Subarrays with K Different Integers            |
| “Repeated calculations”                          | Cache results                 | Memoization                         | Reduced from exponential | Fibonacci DP                                   |
| “Merge multiple sorted lists”                    | Efficient repeated minimum    | Heap                                | O(n log k)               | Merge K Sorted Lists                           |
| “Choose non-overlapping intervals”               | Sort by end time              | Greedy                              | O(n log n)               | Activity Selection                             |
| “Can reach destination?”                         | State traversal               | Greedy / BFS / DP                   | Varies                   | Jump Game                                      |
| “Search in rotated sorted array”                 | Modified ordering logic       | Binary Search                       | O(log n)                 | Rotated Array Search                           |
| “kth smallest/largest”                           | Partial ordering              | Heap, QuickSelect                   | O(n log k) / O(n) avg    | Kth Largest Element                            |
| “Parentheses validation”                         | Nested structure tracking     | Stack                               | O(n)                     | Valid Parentheses                              |
| “Expression evaluation”                          | Operator precedence handling  | Stack                               | O(n)                     | Basic Calculator                               |
