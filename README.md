# Leetcode_solutions
My LeetCode problem solutions in Python
🌀 LeetCode #54 — Spiral Matrix
 📘 Problem Description  
Given an `m x n` matrix, return all the elements of the matrix in **spiral order** — starting from the top-left corner and moving clockwise
🧩 Example

Input: 

matrix = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
]
Output:

[1, 2, 3, 6, 9, 8, 7, 4, 5]

⚙️ Approach

Initialize four boundaries — top, bottom, left, and right.

Traverse:

➡️ Left → Right across the top row

⬇️ Top → Bottom down the right column

⬅️ Right → Left across the bottom row (if remaining)

⬆️ Bottom → Top up the left column (if remaining)

After each traversal, move the boundary inward.

Repeat until all elements are visited.
⏱️ Time & Space Complexity
Explanation:
🕒 Time	O(m * n) — each element is visited exactly once
💾 Space	O(1) — excluding the output list

🧠 Language Used
Python 3

🏁 Status
✅ Accepted on LeetCode

⭐ If you like this solution, consider starring the repo to support my coding journey!
