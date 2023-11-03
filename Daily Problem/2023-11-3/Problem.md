[问题链接](https://codeforces.com/problemset/problem/1854/A2)

⠀

**这个问题的两个版本之间的唯一区别是对最大操作次数的限制。只有所有版本的问题都解决了，你才能进行破解。

给你一个整数数组 $a_1, a_2,\dots, a_n$ （正数、负数或 $0$ ）。您可以对数组进行多种运算（可能是 $0$ 种运算）。

在一次操作中，你选择 $i, j$ （ $1 \leq i, j \leq n$ ，它们可以相等）并设置 $a_i := a_i + a_j$ （即，将 $i, j$ 与 $1 \leq i, j \leq n$ 相加）。(即把 $a_j$ 加到 $a_i$ ）。

使数组不递减（即用 $a_i \leq a_{i+1}$ 代替 $1 \leq i \leq n-1$ ），最多需要进行 $31$ 次操作。您不需要尽量减少操作次数。