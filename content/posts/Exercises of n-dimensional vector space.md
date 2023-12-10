+++
title = "Exercises of n-dimensional vector space"
date = 2023-12-02T00:00:00+08:00
lastmod = 2023-12-10T08:27:23+08:00
tags = ["Advanced Algebra"]
draft = false
toc = true
+++

1.  Suppose the \\(s \times n\\) matrix on field \\(K\\)
    \\[
       A =
       {\begin{pmatrix}
       a\_{11} & a\_{12} & \cdots & a\_{1n}\\\\
       a\_{21} & a\_{22} & \cdots & a\_{2n}\\\\
       \vdots & \vdots &  & \vdots\\\\
       a\_{s1} & a\_{s2} & \cdots & a\_{sn}\\\\
       \end{pmatrix}}
       \\]
    satisfies \\(s \le n\\), and
    \\[2|a\_{ii}|>\sum\_{j=1}^{n}{|a\_{ij}|},\ \ (i = 1, 2, \cdots, s),\\]
    proof: rank of \\(A\\)'s row vector group, \\(\gamma\_{1}\\), \\(\gamma\_{2}\\), &ctdot;, \\(\gamma\_{s}\\), equals to \\(s\\).

    Let
    \\[
       A' =
       {\begin{pmatrix}
       a\_{11} & a\_{12} & \cdots & a\_{1s}\\\\
       a\_{21} & a\_{22} & \cdots & a\_{2s}\\\\
       \vdots & \vdots &  & \vdots\\\\
       a\_{s1} & a\_{s2} & \cdots & a\_{ss}\\\\
       \end{pmatrix}}
       \\]
    We can know \\(\det{A'} \ne 0\\) because
    \\[|a\_{ii}|>\sum\_{j=1 \\\j\ne i}^{s}{|a\_{ij}|},\ \ (i = 1, 2, \cdots, s),\\]
    so rank of \\(A'\\)'s row vector group equals to s, appending the row vectors, we can show that rank of \\(A\\)'s row vector group equals to s.
