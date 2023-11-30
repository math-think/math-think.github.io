+++
title = "Fibonacci numbers and determinant"
date = 2023-11-29T00:00:00+08:00
lastmod = 2023-11-30T14:12:14+08:00
tags = ["Algebra"]
draft = false
toc = true
+++

Fibonacci sequence is a sequence as

\\[1, 2, 3, 5, 8, 13, 21, 34, \cdots,\\]

it satisfies: \\(F\_n = F\_{n - 1} + F\_{n - 2}(n \ge 3), F\_1 = 1, F\_2 = 2\\)

1.  Proof the Fibonacci numbers \\(F\_n\\) can be get from the determinant
    \\[
       F\_n =
       {\begin{vmatrix}
       1 & -1 & 0 & 0 & \cdots & 0 & 0 & 0\\\\
       1 & 1 & -1 & 0 & \cdots & 0 & 0 & 0\\\\
       0 & 1 & 1 & -1 & \cdots & 0 & 0 & 0\\\\
       \vdots & \vdots & \vdots & \vdots & & \vdots & \vdots & \vdots\\\\
       0 & 0 & 0 & 0 & \cdots & 1 & 1 & -1\\\\
       0 & 0 & 0 & 0 & \cdots & 0 & 1 & 1\\\\
       \end{vmatrix} };
       \\]

    <div class="PROOF">

    Use induction can proof it.

    </div>
2.  Show the formula of Fibonacci numbers

    Because \\(F\_n = F\_{n - 1} + F\_{n - 2}(n \ge 3), F\_1 = 1, F\_2 = 2\\), suppose
    \\[F\_n - aF\_{n - 1} = b(F\_{n - 1} - aF\_{n - 2})\\]
    so
    \\[F\_n = (a + b)F\_{n - 1} - abF\_{n - 2}\\]
    \\[F\_n - bF\_{n - 1} = a(F\_{n - 1} - bF\_{n - 2})\\]
    then we get \\(a + b = 1, ab = -1\\), so
    \\[a = \frac{1 + \sqrt{5}}{2}, b = \frac{1 - \sqrt{5}}{2}\\]
    or
    \\[a = \frac{1 - \sqrt{5}}{2}, b = \frac{1 + \sqrt{5}}{2}\\]
    we consider the first case, because \\(F\_2 = 2, F\_1 = 1\\), so
    \\[F\_n - aF\_{n - 1} = b^{n - 2}(2 - a) = b^{n - 2}(1 + b) = b^{n - 2} + b^{n - 1}\\]
    \\[F\_n - bF\_{n - 1} = a^{n - 2}(2 - b) = a^{n - 2}(1 + a) = a^{n - 2} + a^{n - 1}\\]
    so
    \\[F\_n = \frac{a^{n} + a^{n - 1} - b^{n} - b^{n - 1}}{a - b}\\]
    because \\(ab = -1\\), we can get a more elegant conclusion
    \\[F\_n = \frac{a^{n + 1} - b^{n + 1}}{a - b}\\]
