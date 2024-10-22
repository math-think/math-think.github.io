+++
title = "正规子群, 商群和同态定理"
date = 2023-12-20T00:00:00+08:00
lastmod = 2023-12-20T22:16:14+08:00
tags = ["Abstract Algebra"]
draft = false
toc = true
+++

1.  试证群 \\(G\\) 的指数为 2 的子群一定是 \\(G\\) 的正规子群.

    证明:
    设 \\(H \leq G, [G:H] = 2\\), 则

    -   \\(\forall g \in H, gH = H = Hg\\)

    -   \\(\forall g \notin H, h \in H, gh \notin H, H 的指数为二, 只有两个陪集, 故 gH = G \setminus H, Hg = G \setminus H, 故 gH = G \setminus H = Hg\\)

    因此, H 是正规子群.
