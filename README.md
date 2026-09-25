# Python DSA — Complete Interview Preparation Repository

This repository is a structured Python Data Structures & Algorithms (DSA) learning and interview-preparation project.

The repository is designed so that every folder has a clear purpose and every problem contains enough context for a developer or AI coding assistant to understand exactly what needs to be implemented without guessing.

---

## 1. Project Structure

```text
src/
└── dsa/
    ├── common/
    │
    ├── arrays/
    │   ├── basics/
    │   ├── prefix_sum/
    │   ├── sliding_window/
    │   ├── two_pointer/
    │   ├── kadane/
    │   └── matrix/
    │
    ├── strings/
    │   ├── basics/
    │   ├── frequency/
    │   ├── pattern_matching/
    │   ├── sliding_window/
    │   └── advanced/
    │
    ├── linked_list/
    │   ├── basics/
    │   ├── doubly/
    │   ├── circular/
    │   └── advanced/
    │
    ├── stack/
    │   ├── basics/
    │   ├── monotonic/
    │   └── advanced/
    │
    ├── queue/
    │   ├── basics/
    │   ├── deque/
    │   ├── priority_queue/
    │   └── advanced/
    │
    ├── hashing/
    │   ├── basics/
    │   ├── frequency/
    │   └── advanced/
    │
    ├── recursion/
    │   ├── basics/
    │   └── advanced/
    │
    ├── backtracking/
    │   ├── permutations/
    │   ├── combinations/
    │   ├── subsets/
    │   └── advanced/
    │
    ├── trees/
    │   ├── binary_tree/
    │   │   ├── traversals/
    │   │   ├── basics/
    │   │   ├── properties/
    │   │   └── advanced/
    │   ├── bst/
    │   ├── avl/
    │   ├── red_black_tree/
    │   ├── heap/
    │   ├── trie/
    │   ├── segment_tree/
    │   ├── fenwick_tree/
    │   ├── b_tree/
    │   ├── suffix_tree/
    │   └── merkle_tree/
    │
    ├── graphs/
    │   ├── representation/
    │   ├── bfs/
    │   ├── dfs/
    │   ├── cycle_detection/
    │   ├── topological_sort/
    │   ├── shortest_path/
    │   ├── minimum_spanning_tree/
    │   ├── disjoint_set/
    │   └── advanced/
    │
    ├── binary_search/
    │   ├── basics/
    │   ├── first_last_position/
    │   ├── rotated_array/
    │   ├── peak/
    │   ├── search_on_answer/
    │   └── advanced/
    │
    ├── sorting/
    │   ├── basic/
    │   ├── comparison/
    │   ├── non_comparison/
    │   └── advanced/
    │
    ├── greedy/
    │   ├── basics/
    │   ├── intervals/
    │   ├── scheduling/
    │   └── advanced/
    │
    ├── dynamic_programming/
    │   ├── basics/
    │   ├── one_dimension/
    │   ├── two_dimension/
    │   ├── knapsack/
    │   ├── subsequence/
    │   ├── string_dp/
    │   ├── grid/
    │   ├── interval_dp/
    │   ├── tree_dp/
    │   ├── bitmask_dp/
    │   └── advanced/
    │
    ├── bit_manipulation/
    │   ├── basics/
    │   ├── bitwise_tricks/
    │   └── advanced/
    │
    ├── math/
    │   ├── basics/
    │   ├── prime_numbers/
    │   ├── gcd_lcm/
    │   ├── modular_arithmetic/
    │   ├── combinatorics/
    │   └── advanced/
    │
    ├── advanced_data_structures/
    │   ├── ordered_set/
    │   ├── interval_tree/
    │   ├── disjoint_set/
    │   ├── sparse_table/
    │   └── sqrt_decomposition/
    │
    ├── algorithms/
    │   ├── divide_and_conquer/
    │   ├── randomized/
    │   ├── meet_in_the_middle/
    │   └── bitmask/
    │
    └── patterns/
        ├── two_pointer/
        ├── sliding_window/
        ├── fast_slow_pointer/
        ├── merge_intervals/
        ├── binary_search/
        ├── monotonic_stack/
        ├── top_k/
        ├── union_find/
        └── prefix_sum/

tests/
├── arrays/
├── strings/
├── linked_list/
├── stack/
├── queue/
├── hashing/
├── recursion/
├── backtracking/
├── trees/
├── graphs/
├── binary_search/
├── sorting/
├── greedy/
├── dynamic_programming/
├── bit_manipulation/
├── math/
└── algorithms/
```

---

# 2. Repository Goal

The goal is to build a complete DSA knowledge base containing:

- Data structures
- Algorithms
- Interview problems
- Problem-solving patterns
- Brute-force solutions
- Optimized solutions
- Complexity analysis
- Operation analysis
- Edge cases
- Automated tests
- Interview explanations
- AI-friendly problem context

The repository should help answer not only:

> "What is the solution?"

but also:

> "Why does this solution work?"

---

# 3. Problem Difficulty

Problems should be organized conceptually in this order:

```text
HARD
MEDIUM
EASY
```

Every problem must specify:

```text
Difficulty: HARD
```

or:

```text
Difficulty: MEDIUM
```

or:

```text
Difficulty: EASY
```

Difficulty describes the expected reasoning and implementation difficulty.

---

# 4. Problem Specification

Every problem must provide enough information for another developer or AI assistant to understand the exact requirement.

Use this structure:

```text
Problem ID
Title
Difficulty
Topic
Pattern
Prerequisites

Problem Description

Input
Output
Constraints

Examples

Expected Behavior
Important Rules
Edge Cases

Brute Force Approach
Better Approach
Optimal Approach

Time Complexity
Space Complexity
Operation Count

Common Mistakes
Interview Explanation
Related Problems
```

The important principle is:

> Never make the AI guess an important requirement.

---

# 5. Example Problem Specification

```text
Problem ID:
ARRAY-001

Title:
Maximum Subarray Sum

Difficulty:
MEDIUM

Topic:
Arrays

Pattern:
Kadane's Algorithm

Description:
Given an integer array, find the maximum sum of a
non-empty contiguous subarray.

Input:
numbers: list[int]

Output:
int

Constraints:
1 <= len(numbers) <= 100000
-10^9 <= numbers[i] <= 10^9

Important Rules:
- The subarray must be non-empty.
- The elements must be contiguous.

Example:

Input:
[-2,1,-3,4,-1,2,1,-5,4]

Output:
6

Explanation:
[4,-1,2,1] has the maximum sum.

Edge Cases:
[-5] -> -5
[-5,-2,-8] -> -2
[1,2,3] -> 6
```

---

# 6. One Problem Per File

Prefer one main problem per Python file.

Example:

```text
src/dsa/arrays/basics/
├── find_maximum.py
├── find_minimum.py
├── second_largest.py
├── reverse_array.py
└── rotate_array.py
```

This makes:

- Testing easier
- Debugging easier
- Git history cleaner
- AI-assisted development easier
- Revision easier

---

# 7. Arrays

```text
arrays/
├── basics/
├── prefix_sum/
├── sliding_window/
├── two_pointer/
├── kadane/
└── matrix/
```

## basics

Fundamental array operations:

- Traversal
- Search
- Maximum/minimum
- Second largest
- Reverse
- Rotation
- Duplicate handling
- In-place operations

## prefix_sum

Study:

- Prefix sum
- Range sum
- Subarray sum
- Difference arrays
- Prefix/suffix techniques

Core question:

> Can previously calculated cumulative information remove repeated work?

## sliding_window

Study:

- Fixed-size window
- Variable-size window
- Longest valid window
- Shortest valid window
- Window frequency
- Maximum/minimum window

## two_pointer

Study:

- Opposite-direction pointers
- Same-direction pointers
- Sorted arrays
- Pair problems
- In-place transformations

## kadane

Study:

- Maximum subarray
- Minimum subarray
- Index tracking
- Circular subarray variants

## matrix

Study:

- Matrix traversal
- Transpose
- Rotation
- Spiral traversal
- Matrix search
- Row/column operations

---

# 8. Strings

```text
strings/
├── basics/
├── frequency/
├── pattern_matching/
├── sliding_window/
└── advanced/
```

## basics

- Character traversal
- Reverse
- Palindrome
- Substrings
- String transformation

## frequency

- Character frequency
- Anagrams
- Duplicate characters
- Frequency maps

## pattern_matching

Study:

- KMP
- Rabin-Karp
- Z algorithm
- Pattern searching

## sliding_window

Study:

- Longest substring
- Shortest substring
- Character constraints
- Anagram windows

## advanced

Advanced string algorithms and structures.

---

# 9. Linked List

```text
linked_list/
├── basics/
├── doubly/
├── circular/
└── advanced/
```

## basics

- Traversal
- Insert
- Delete
- Reverse
- Find middle
- Merge lists

## doubly

Operations involving:

```text
previous <-> current <-> next
```

## circular

Circular list traversal and modification.

## advanced

- Cycle detection
- Reordering
- Complex pointer manipulation
- Advanced linked-list problems

---

# 10. Stack

```text
stack/
├── basics/
├── monotonic/
└── advanced/
```

## basics

- Push
- Pop
- Peek
- Valid parentheses
- Expression evaluation

## monotonic

- Increasing stack
- Decreasing stack
- Next greater element
- Next smaller element
- Largest rectangle

## advanced

Advanced stack algorithms.

---

# 11. Queue

```text
queue/
├── basics/
├── deque/
├── priority_queue/
└── advanced/
```

## basics

FIFO operations.

## deque

Double-ended queue problems.

## priority_queue

- Min heap
- Max heap
- Top K
- Scheduling
- Priority-based processing

## advanced

Complex queue/deque/heap combinations.

---

# 12. Hashing

```text
hashing/
├── basics/
├── frequency/
└── advanced/
```

Study:

- Hash maps
- Hash sets
- Lookup optimization
- Frequency counting
- Grouping
- Prefix sum + hashing

Core question:

> Can hashing reduce repeated searching?

---

# 13. Recursion

```text
recursion/
├── basics/
└── advanced/
```

Every recursive problem should identify:

```text
Base case
Recursive state
Recursive transition
Return value
```

---

# 14. Backtracking

```text
backtracking/
├── permutations/
├── combinations/
├── subsets/
└── advanced/
```

Every backtracking problem should identify:

```text
Choice
Constraint
State
Recursive call
Undo/backtrack
```

Study:

- Permutations
- Combinations
- Subsets
- Constraint problems
- N-Queens
- Sudoku

---

# 15. Trees

```text
trees/
├── binary_tree/
├── bst/
├── avl/
├── red_black_tree/
├── heap/
├── trie/
├── segment_tree/
├── fenwick_tree/
├── b_tree/
├── suffix_tree/
└── merkle_tree/
```

## binary_tree/traversals

- Preorder
- Inorder
- Postorder
- Level order
- Recursive traversal
- Iterative traversal

## binary_tree/basics

- Height
- Depth
- Search
- Insert
- Delete
- Tree construction

## binary_tree/properties

- Balanced tree
- Diameter
- Width
- Complete tree
- Full tree
- Symmetry
- Lowest common ancestor

## binary_tree/advanced

Advanced binary-tree algorithms.

## bst

Study:

- Search
- Insert
- Delete
- Minimum/maximum
- Successor/predecessor
- Validation

## avl

Study:

- Balance factor
- Left rotation
- Right rotation
- Insert
- Delete

## red_black_tree

Study:

- Node colors
- Rotations
- Rebalancing
- Insert/delete

## heap

Study:

- Min heap
- Max heap
- Heapify
- Heap sort
- Priority queue

## trie

Study:

- Insert
- Search
- Prefix search
- Autocomplete
- Word problems

## segment_tree

Study:

- Range query
- Point update
- Range update
- Lazy propagation where required

## fenwick_tree

Study:

- Prefix query
- Point update
- Range calculations

## b_tree

Study multi-way balanced search trees and their operations.

## suffix_tree

Study advanced string indexing and suffix-based queries.

## merkle_tree

Study hash-based tree construction and verification.

---

# 16. Graphs

```text
graphs/
├── representation/
├── bfs/
├── dfs/
├── cycle_detection/
├── topological_sort/
├── shortest_path/
├── minimum_spanning_tree/
├── disjoint_set/
└── advanced/
```

## representation

- Adjacency list
- Adjacency matrix
- Edge list
- Directed graph
- Undirected graph
- Weighted graph

## bfs

- Graph traversal
- Level traversal
- Unweighted shortest path

## dfs

- Recursive DFS
- Iterative DFS
- Connected components

## cycle_detection

- Directed graph
- Undirected graph
- DFS
- Union-Find

## topological_sort

- Kahn's algorithm
- DFS ordering
- Dependency problems

## shortest_path

Study:

- BFS
- Dijkstra
- Bellman-Ford
- Floyd-Warshall

## minimum_spanning_tree

Study:

- Kruskal
- Prim

## disjoint_set

Study:

- Find
- Union
- Path compression
- Union by rank/size

## advanced

Advanced graph algorithms.

---

# 17. Binary Search

```text
binary_search/
├── basics/
├── first_last_position/
├── rotated_array/
├── peak/
├── search_on_answer/
└── advanced/
```

Every binary-search problem should explain:

> What property allows the search space to be reduced?

Study:

- Basic binary search
- First position
- Last position
- Lower bound
- Upper bound
- Rotated arrays
- Peak finding
- Binary search on answer

---

# 18. Sorting

```text
sorting/
├── basic/
├── comparison/
├── non_comparison/
└── advanced/
```

## basic

- Bubble sort
- Selection sort
- Insertion sort

## comparison

- Merge sort
- Quick sort
- Heap sort

## non_comparison

- Counting sort
- Radix sort
- Bucket sort

## advanced

Advanced sorting algorithms and optimizations.

Every sorting algorithm should document:

```text
Best case
Average case
Worst case
Space complexity
Stable?
In-place?
```

---

# 19. Greedy

```text
greedy/
├── basics/
├── intervals/
├── scheduling/
└── advanced/
```

Every greedy problem should explain:

```text
Local choice
Why the choice is safe
Why the strategy produces the required result
```

Study:

- Activity selection
- Interval problems
- Scheduling
- Resource allocation
- Job sequencing

---

# 20. Dynamic Programming

```text
dynamic_programming/
├── basics/
├── one_dimension/
├── two_dimension/
├── knapsack/
├── subsequence/
├── string_dp/
├── grid/
├── interval_dp/
├── tree_dp/
├── bitmask_dp/
└── advanced/
```

Every DP problem must identify:

```text
State
Transition
Base case
Answer
Iteration order
```

## basics

- Overlapping subproblems
- Optimal substructure
- Memoization
- Tabulation

## one_dimension

Examples:

- Fibonacci
- Climbing stairs
- House robber

## two_dimension

Two-dimensional state problems.

## knapsack

- 0/1 knapsack
- Unbounded knapsack
- Subset sum
- Partition

## subsequence

- LIS
- LCS
- Subsequence optimization

## string_dp

- Edit distance
- Palindromic subsequence
- String transformations

## grid

Grid-based DP.

## interval_dp

DP where the state represents an interval.

## tree_dp

DP over tree nodes/subtrees.

## bitmask_dp

DP where a bitmask represents a state/set.

## advanced

Advanced DP optimization techniques.

---

# 21. Bit Manipulation

```text
bit_manipulation/
├── basics/
├── bitwise_tricks/
└── advanced/
```

Study:

```text
AND
OR
XOR
NOT
Left Shift
Right Shift
Bit masks
Set bit
Clear bit
Toggle bit
Count bits
Power of two
XOR tricks
```

---

# 22. Math / Number Theory

```text
math/
├── basics/
├── prime_numbers/
├── gcd_lcm/
├── modular_arithmetic/
├── combinatorics/
└── advanced/
```

## basics

Basic mathematical algorithms.

## prime_numbers

- Prime checking
- Sieve of Eratosthenes
- Prime factorization

## gcd_lcm

- Euclidean algorithm
- GCD
- LCM

## modular_arithmetic

- Modular addition
- Modular multiplication
- Fast exponentiation
- Modular inverse

## combinatorics

- Permutations
- Combinations
- Counting

## advanced

Advanced number theory.

---

# 23. Advanced Data Structures

```text
advanced_data_structures/
├── ordered_set/
├── interval_tree/
├── disjoint_set/
├── sparse_table/
└── sqrt_decomposition/
```

For every advanced structure document:

```text
What problem does it solve?
Why is a normal structure insufficient?
Supported operations
Construction complexity
Query complexity
Update complexity
Space complexity
Typical use cases
```

---

# 24. Algorithms

```text
algorithms/
├── divide_and_conquer/
├── randomized/
├── meet_in_the_middle/
└── bitmask/
```

## divide_and_conquer

Identify:

```text
Divide
Solve
Combine
```

## randomized

Document:

- Randomization
- Expected complexity
- Probability assumptions

## meet_in_the_middle

Split a large search space into smaller parts.

## bitmask

Use binary representation to represent sets or states.

---

# 25. Common Patterns

```text
patterns/
├── two_pointer/
├── sliding_window/
├── fast_slow_pointer/
├── merge_intervals/
├── binary_search/
├── monotonic_stack/
├── top_k/
├── union_find/
└── prefix_sum/
```

Every pattern should contain:

```text
Recognition clues
Core idea
Invariant
General template
Time complexity
Space complexity
Common mistakes
Example problems
```

The purpose of this directory is to teach:

> How to recognize a pattern from a new interview problem.

---

# 26. Important Special Rule: Merge Intervals

Problem requirements must explicitly define whether touching intervals merge.

For example:

```text
[1,2]
[2,3]
```

If the requirement is:

```text
Touching intervals MUST NOT merge.
```

then:

```text
Expected:
[1,2]
[2,3]
```

The implementation must use the appropriate strict comparison.

Never infer this behavior from the problem title alone.

---

# 27. Tests

Tests mirror the DSA categories:

```text
tests/
├── arrays/
├── strings/
├── linked_list/
├── stack/
├── queue/
├── hashing/
├── recursion/
├── backtracking/
├── trees/
├── graphs/
├── binary_search/
├── sorting/
├── greedy/
├── dynamic_programming/
├── bit_manipulation/
├── math/
└── algorithms/
```

Tests should verify:

- Normal cases
- Minimum input
- Maximum/boundary input
- Empty input when valid
- Single element
- Duplicate values
- Negative values
- Special rules
- Invalid input when applicable

---

# 28. Test Naming

Prefer descriptive names:

```python
def test_find_maximum_returns_largest_value():
    ...


def test_find_maximum_handles_negative_values():
    ...


def test_find_maximum_handles_single_element():
    ...
```

Avoid:

```python
def test_1():
    ...
```

---

# 29. Solution Levels

For important problems, explain:

```text
1. Brute Force
2. Better Approach
3. Optimal Approach
```

Not every problem needs three implementations.

The explanation should include:

```text
What is the idea?
Why does it work?
What is the bottleneck?
How is the bottleneck removed?
What invariant is maintained?
```

---

# 30. Complexity

Every algorithm should state:

```text
Time Complexity:
O(...)

Space Complexity:
O(...)
```

Do not calculate complexity only from the number of visible loops.

Analyze the actual work performed.

Examples:

```text
O(1)
O(log n)
O(n)
O(n log n)
O(n²)
O(2^n)
O(n!)
```

---

# 31. Operation Count

For selected problems, provide approximate operation analysis.

Example:

```text
Input size = n

Single pass:
approximately n comparisons

Nested full loops:
approximately n² comparisons

Binary search:
approximately log2(n) iterations
```

Operation counting is for intuition.

Big-O remains the primary complexity measurement.

---

# 32. Common Mistakes

Difficult problems should document common mistakes.

Example:

```text
Problem:
Merge Intervals

Potential mistake:
Using <= instead of < when touching intervals must remain separate.

Wrong:
if current_start <= previous_end:

Correct for this requirement:
if current_start < previous_end:
```

---

# 33. Interview Explanation

Important problems should have a short explanation suitable for an interview.

Example:

```text
I use two pointers starting from both ends.

At every step, the smaller value limits the result,
so I move the pointer associated with the smaller value.

This reduces the search space while preserving the possibility
of finding the maximum result.
```

The explanation should be understandable without reading the code.

---

# 34. AI / ChatGPT Contract

This repository is designed to work with AI tools.

When asking ChatGPT or another AI to work on a problem, provide:

```text
File path
Problem ID
Problem description
Input
Output
Constraints
Examples
Important rules
Existing implementation
Expected tests
Required approach
```

Example:

```text
Work on:

src/dsa/arrays/two_pointer/container_with_most_water.py

Requirements:

- Solve using two pointers.
- Do not modify the input.
- Explain the invariant.
- Include time complexity.
- Include space complexity.
- Add edge-case tests.
- Do not modify unrelated files.
```

---

# 35. AI Rules

An AI coding assistant working on this repository should:

1. Read the target problem first.
2. Read related tests.
3. Read relevant common utilities.
4. Never guess an ambiguous requirement.
5. Preserve explicit rules.
6. Avoid modifying unrelated files.
7. Explain the solution.
8. Explain complexity.
9. Add/update tests.
10. Run tests when possible.
11. Follow the repository's Python style.
12. Keep the implementation readable.
13. Prefer the requested algorithm when one is specified.
14. If no algorithm is specified, explain alternatives before selecting the expected interview approach.

---

# 36. Study Workflow

For every problem:

```text
1. Understand the problem.
2. Identify input and output.
3. Identify constraints.
4. Identify important rules.
5. Identify edge cases.
6. Solve brute force.
7. Calculate complexity.
8. Find the bottleneck.
9. Optimize.
10. Implement.
11. Write tests.
12. Run tests.
13. Review mistakes.
14. Prepare interview explanation.
```

---

# 37. Recommended Learning Order

```text
01. Arrays
02. Strings
03. Hashing
04. Linked List
05. Stack
06. Queue
07. Binary Search
08. Sorting
09. Recursion
10. Backtracking
11. Trees
12. Heap
13. Trie
14. Graphs
15. Greedy
16. Dynamic Programming
17. Bit Manipulation
18. Math / Number Theory
19. Advanced Data Structures
20. Advanced Algorithms
21. Interview Patterns
```

---

# 38. Definition of Done

A problem is complete when:

```text
[ ] Problem ID added
[ ] Title added
[ ] Difficulty added
[ ] Topic added
[ ] Pattern added
[ ] Prerequisites documented
[ ] Problem statement written
[ ] Input documented
[ ] Output documented
[ ] Constraints documented
[ ] Examples added
[ ] Important rules documented
[ ] Edge cases documented
[ ] Solution implemented
[ ] Complexity documented
[ ] Tests added
[ ] Tests pass
[ ] Common mistakes documented
[ ] Interview explanation added
```

---

# 39. Git Commit Convention

Use clear commit messages:

```text
feat(arrays): add maximum subarray
feat(graphs): add bfs traversal
feat(dp): add climbing stairs
test(arrays): add rotate array edge cases
docs(trees): document bst deletion
refactor(common): improve tree utilities
```

---

# 40. Golden Rule

Do not memorize the solution.

For every problem, you should be able to answer:

```text
What exactly is the problem asking?

What are the constraints?

What is the brute-force solution?

Why is brute force slow?

What observation allows optimization?

What invariant does the solution maintain?

What are the edge cases?

What is the time complexity?

What is the space complexity?

Can I explain the solution clearly in an interview?
```

If these questions can be answered, the problem has been understood rather than merely memorized.

---

# 41. Final Repository Principle

The repository should eventually become:

```text
DSA Knowledge Base
        +
Problem Library
        +
Algorithm Implementations
        +
Automated Tests
        +
Complexity Analysis
        +
Interview Notes
        +
Reusable Patterns
        +
AI-Friendly Context
```

The folder structure already created is the foundation.

**Do not create another folder structure.**

Add problems inside the existing folders according to the rules in this README.
