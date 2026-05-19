
Coding strategy : 

Rephrase the question to make sure you understood what the interviewer asked 

✅ Ask Clarifying questions (at least 3)

✅ Write test cases (at least 3) with input & output - focus on the edge cases

✅ Find a brute force solution in 3 minutes (If you can't, ask for the hint)

✅ Figure out how to optimize the solution, 90% of the time it will be a time-space trade-off (the other
10% some clever/neat tricks on how your algorithm works using the special property of the given
problem - the first step is important)

✅ Thinking out loud (Talk with your interviewer) - figure out what is acceptable and what's not, and ask if
you can start coding

✅ Write clean code in your preferred language where you know all the data structures & libraries

✅ Manually test your code using the test cases you wrote in the third step

✅ Fix the bug if you find any and then talk about your run time & space complexity with the interviewer

✅ Let the interviewer know you are done, any anything you should try to improve/optimize



# My coding feedback
* didnt explain how to solve problem 
* coding slow , may be use python 
* brute force solution quick and time complexity
* clean code : variable naming , format issues use visual studio code 




------------
------------------

## Patterns 
Pattern 01 — Sliding Window How to process contiguous subarrays in a single pass. Turns O(n²) brute force into O(n) by maintaining a moving window that adds one element and removes another instead of recomputing from scratch. Covers maximum subarray, longest substring with k distinct characters, and minimum window problems.

Pattern 02 — Two Pointers Navigate sorted arrays from both ends simultaneously. Eliminates nested loops and reduces quadratic solutions to linear time. The pattern behind two sum, container with most water, and three sum — three of the most common FAANG warm-up problems.

Pattern 03 — Fast & Slow Pointers Floyd's Tortoise and Hare algorithm. One pointer moves one step, one moves two. If a cycle exists, they meet. If not, fast reaches the end. Solves cycle detection, finding the middle of a linked list, and happy number — all in O(1) space.

Pattern 04 — Merge Intervals Sort by start time, then merge overlapping ranges in a single linear pass. The pattern behind meeting room scheduling, calendar overlap detection, and any problem where intervals need to be combined, split, or analyzed for coverage.

Pattern 05 — Cyclic Sort If you have n numbers in range [1, n], each number belongs at a specific index. Place them there in one pass. Then a second pass finds every missing, duplicate, or misplaced number in O(n) time with O(1) space — no hash maps, no sorting overhead.

Pattern 06 — In-Place Linked List Reversal Reverse a linked list — or any sublist — by rewiring three pointers as you traverse. No extra data structures. Covers full reversal, partial reversal between positions p and q, k-group reversal, and palindrome detection on linked lists.

Pattern 07 — Tree BFS Process trees level by level using a queue. The snapshot trick — capturing the queue size at the start of each level — is the single technique that unlocks level-order traversal, minimum depth, right-side view, and zigzag traversal problems.

Pattern 08 — Tree DFS Explore tree paths fully before backtracking, using recursion or an explicit stack. The three traversal orders — preorder, inorder, postorder — and when each applies. Covers path sum, maximum depth, BST validation, and all root-to-leaf path problems.

Pattern 09 — Two Heaps A max-heap holding the lower half of your data. A min-heap holding the upper half. Keep them balanced and the median lives at the top in O(1). The only pattern that solves the median of a data stream problem efficiently — and a guaranteed appearance in senior-level loops.

Pattern 10 — Subsets & Backtracking Build solutions incrementally: choose, recurse, un-choose. Every path in the decision tree is a candidate solution. Generates all subsets, permutations, and combinations systematically. Solves Sudoku, N-Queens, word search, and every combinatorial problem at FAANG.

Pattern 11 — Modified Binary Search Binary search does not require a fully sorted array. Learn to identify which half is always sorted in a rotated array, how to binary search on the answer space rather than the array itself, and how to find first and last positions in O(log n). Covers six variations most candidates have never practiced.

Pattern 12 — Top K Elements A min-heap of size K always holds the K largest elements. Its root is the Kth largest by definition. More efficient than sorting when K is small. Solves K most frequent elements, K closest points to origin, Kth largest in a stream, and top K frequent words.
