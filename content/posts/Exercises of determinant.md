+++
title = "Exercises of determinant"
date = 2023-11-26T00:00:00+08:00
lastmod = 2023-11-30T22:07:08+08:00
tags = ["Algebra"]
draft = false
toc = true
+++

1.  Suppose \\(n\ge 2\\)，show that if the elements of a \\(n \times n\\) matrix \\(A\\) are 1 or -1, then \\(|A|\\) must be an even number.

    <div class="PROOF">

    Consider the symmetries of \\(a\_{1i}\\), \\(a\_{2j}\\) and \\(a\_{1j}\\), \\(a\_{2i}\\), the value of corresponding determinant of the \\(2 \times 2\\) matrix must be an even number, so the n-order determinant must be an even number.

    </div>
2.  Does \\(f(x,y,z)=x^3+y^3+z^3-3xyz\\) has a factor which is of degree 1? if yes, show it.

     \\[
       x^3+y^3+z^3-3xyz =
       {\begin{vmatrix}
       x & y & z\\\\
       y & z & x\\\\
       z & x & y
       \end{vmatrix}}
       \\]
     this determinant can be transformed to
     \\[
       (x+y+z) \times
       {\begin{vmatrix}
       1 & 1 & 1\\\\
       y & z & x\\\\
       z & x & y
       \end{vmatrix}}
       \\]
    so \\((x+y+z)\\) is the factor of degree 1.
