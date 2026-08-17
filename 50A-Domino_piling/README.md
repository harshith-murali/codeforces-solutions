# 50A - Domino piling

[View on Codeforces](https://codeforces.com/contest/50/problem/A)

## Constraints

- **Time limit:** 2 seconds
- **Memory limit:** 256 megabytes

## Statement

You are given a rectangular board of M × N squares. Also you are given an unlimited number of standard domino pieces of 2 × 1 squares. You are allowed to rotate the pieces. You are asked to place as many dominoes as possible on the board so as to meet the following conditions:

1. Each domino completely covers two squares.

2. No two dominoes overlap.

3. Each domino lies entirely inside the board. It is allowed to touch the edges of the board.

Find the maximum number of dominoes, which can be placed under these restrictions.

## Input

In a single line you are given two integers M and N — board sizes in squares (1 ≤ M ≤ N ≤ 16).

## Output

Output one number — the maximal number of dominoes, which can be placed.

## Examples

**Sample Input 1:**
```
2 4
```

**Sample Output 1:**
```
4
```

**Sample Input 2:**
```
3 3
```

**Sample Output 2:**
```
4
```

---

Solved in **C++17 (GCC 7-32)** — verdict: Accepted.
[Submission](https://codeforces.com/contest/50/submission/347911594)
