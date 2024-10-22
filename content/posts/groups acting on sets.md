+++
title = "群在集合上的作用"
date = 2024-01-21T00:00:00+08:00
lastmod = 2024-01-22T02:05:18+08:00
tags = ["Abstract Algebra"]
draft = false
toc = true
+++

## 例题 {#例题}

1.  设群 \\(G\\) 作用在集合 &Sigma; 上. 令 \\(t\\) 表示 &Sigma; 在 \\(G\\) 作用下的轨道个数,
    对任意 \\(g \in G\\), \\(f(g)\\) 表示 &epsilon; 在 \\(g\\) 作用下的不动点个数. 试证
    \\[\sum\_{g \in G}{f(g)} = t|G|.\\]
    这就是说, \\(G\\) 的每个元素在 &Sigma; 上作用平均使得 \\(t\\) 个文字不动.

    证明:

    \\[\sum\_{g \in G}f(g) = \sum\_{a \in \Sigma}|G\_{a}| = \sum\_{a \in \Sigma}\frac{|G|}{|[a]|} = \sum\_{i = 1}^t\sum\_{j = 1}^{|[a\_i]|}\frac{|G|}{|[a\_i]|} = t|G|.\\]

    证毕.
