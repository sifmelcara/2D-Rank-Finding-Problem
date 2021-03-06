# 2D Rank Finding Problem

Solve 2D Rank Finding Problem in Several Languages

## Description

- P<sub>i</sub>(x<sub>i</sub>, y<sub>i</sub>) **dominates** P<sub>j</sub>(x<sub>j</sub>, y<sub>j</sub>) iff x<sub>i</sub> ≥ x<sub>j</sub> and y<sub>i</sub> ≥ y<sub>j</sub>
- Given a set of points, the **rank** of a point is the number of points dominated by it.

Design a program to find the rank of each point.

## Input

Input consists several test cases.

Each case starts with a line containing an integer n, where n denotes the number of points.<br>
The next n lines give the x and y coordinates of the points.

The input ends with a zero for n.

- 5 ≤ n ≤ 100000
- -2147483648 ≤ x, y ≤ 2147483647
- n ∈ N
- x, y ∈ Z

## Output

Your output should consist of a single line for each test case containing n numbers, the rank of each point.

## Sample Input

```
5
1 4
6 2
8 0
2 7
7 5
7
1 2
-3 -4
5 6
-7 -8
3 7
-5 -9
0 0
0
```

## Sample Output

```
0 0 0 1 2
4 2 5 0 5 0 3
```
