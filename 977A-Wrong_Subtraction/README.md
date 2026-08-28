# 977A - Wrong Subtraction

[View on Codeforces](https://codeforces.com/contest/977/problem/A)

## Constraints

- **Time limit:** 1 second
- **Memory limit:** 256 megabytes

## Statement

Little girl Tanya is learning how to decrease a number by one, but she does it wrong with a number consisting of two or more digits. Tanya subtracts one from a number by the following algorithm:

- if the last digit of the number is non-zero, she decreases the number by one;
- if the last digit of the number is zero, she divides the number by 10 (i.e. removes the last digit).

You are given an integer number $n$. Tanya will subtract one from it $k$ times. Your task is to print the result after all $k$ subtractions.

It is guaranteed that the result will be positive integer number.

## Input

The first line of the input contains two integer numbers $n$ and $k$ ($2 \le n \le 10^9$, $1 \le k \le 50$) — the number from which Tanya will subtract and the number of subtractions correspondingly.

## Output

Print one integer number — the result of the decreasing $n$ by one $k$ times.

It is guaranteed that the result will be positive integer number.

## Examples

**Sample Input 1:**
```
512 4
```

**Sample Output 1:**
```
50
```

**Sample Input 2:**
```
1000000000 9
```

**Sample Output 2:**
```
1
```

## Note

The first example corresponds to the following sequence: $512 \rightarrow 511 \rightarrow 510 \rightarrow 51 \rightarrow 50$.

---

Solved in **C++17 (GCC 7-32)** — verdict: Accepted.
[Submission](https://codeforces.com/contest/977/submission/388678566)
