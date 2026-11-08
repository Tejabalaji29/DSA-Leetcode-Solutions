# DSA LeetCode Solutions

My solutions to LeetCode problems in Python, written while learning Data Structures and Algorithms. Each solution includes the approach, the key idea, and the time and space complexity.

## Goals

- Build a strong foundation in DSA, one pattern at a time
- Write clean, simple, readable code
- Understand *why* a solution works, not just copy it
- Revisit and re-solve problems without looking at the answer

## How I Approach a Problem

1. **Restate** the problem in my own words
2. **Read the constraints** to guess the target complexity
3. **Solve small examples by hand**
4. **Write the brute force** first as a baseline
5. **Find the bottleneck** and match it to a known pattern
6. **Test edge cases** (empty input, duplicates, negatives, single element)
7. **Note the complexity** and the key insight

## Patterns I'm Practicing

- Arrays and Hashing
- Two Pointers
- Sliding Window
- Linked Lists
- Binary Search
- Stack and Queue
- Trees and Graphs
- Dynamic Programming

## Folder Structure

```
DSA-Leetcode-Solutions/
├── README.md
├── 0001-problem-name/
│   └── solution.py
├── 0002-problem-name/
│   └── solution.py
└── ...
```

If you use the LeetHub extension, it creates this layout automatically on every Accepted submission.

## Solution Template

Each solution file follows this format:

```python
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
```

## Running Locally

LeetCode solutions use a `Solution` class, so to test one locally, add a few lines at the bottom of the file:

```python
if __name__ == "__main__":
    print(Solution().methodName(...))
```

Then run:

```bash
python solution.py
```

## Notes

- Solutions are written in Python 3
- Where a problem has more than one approach, the brute force goes in the notes and the optimal one is the solution

## Connect

- GitHub: [your-username](https://github.com/your-username)
- LeetCode: [your-profile](https://leetcode.com/your-profile)
