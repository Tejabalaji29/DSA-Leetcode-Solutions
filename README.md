# DSA-Leetcode-Solutions
My solutions to LeetCode problems in Python, written while learning Data Structures and Algorithms. Each solution includes the approach, the key idea, and the time and space complexity.

Goals
-> Build a strong foundation in DSA, one pattern at a time
-> Write clean, simple, readable code
-> Understand why a solution works, not just copy it
-> Revisit and re-solve problems without looking at the answer

How I Approach a Problem
Restate the problem in my own words
Read the constraints to guess the target complexity
Solve small examples by hand
Write the brute force first as a baseline
Find the bottleneck and match it to a known pattern
Test edge cases (empty input, duplicates, negatives, single element)
Note the complexity and the key insight
Patterns Covered
Hash Map / Hash Set
Linked List (dummy head, carry)
Sliding Window
Binary Search
Two Pointers (expand from center)
Folder Structure
DSA-Leetcode-Solutions/
├── README.md
├── 0001-two-sum/
│   └── solution.py
├── 0002-add-two-numbers/
│   └── solution.py
├── 0003-longest-substring-without-repeating-characters/
│   └── solution.py
├── 0004-median-of-two-sorted-arrays/
│   └── solution.py
└── 0005-longest-palindromic-substring/
    └── solution.py

If you use the LeetHub extension, it creates this folder layout automatically on every Accepted submission.

Solution Template

Each solution file follows this format:

python
"""
Problem: <number>. <title>
Difficulty: <Easy | Medium | Hard>
Pattern: <pattern name>

Idea:
    <one or two lines on the key insight>

Time:  O(...)
Space: O(...)
"""

class Solution:
    def methodName(self, ...):
        ...
Running Locally

LeetCode solutions use a Solution class, so to test one locally, add a few lines at the bottom of the file:

python
if __name__ == "__main__":
    print(Solution().twoSum([2, 7, 11, 15], 9))  # [0, 1]

Then run:

bash
python solution.py
Progress
Easy: 1
Medium: 3
Hard: 1
Total: 5

Update this section as you solve more problems.

Notes
Solutions are written in Python 3
Problems are grouped by pattern when I review them, not by number
Where a problem has more than one approach, I keep the brute force in the notes and the optimal one as the solution
