+++
title = "正规子群, 商群和同态定理"
date = 2023-12-20T00:00:00+08:00
lastmod = 2023-12-20T23:55:01+08:00
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

2.  设 \\(f: G \rightarrow H\\) 是群同态, \\(M \leq G\\) 试证 \\(f^{-1}(f(M)) = KM\\), 这里 \\(K = \text{Ker} f\\)

    证明:

    \\(\Leftarrow\\) \\(\forall g = km \in KM, f(g) = f(km) = f(k)f(m) = f(m) \in f(M)\\),
    故 \\(g \in f^{-1}(f(M))\\),

    即 \\(KM \subset f^{-1}(f(M))\\).

    \\(\Rightarrow\\) \\(\forall g \in f^{-1}(f(M)), f(g) \in f(M)\\),

    故 \\(\exists m \in M, f(g) = f(m)\\), 而 \\(f(gm^{-1}) = f(m)f(m^{-1}) = 1\_H\\), 故 \\(g = gm^{-1}m \in KM\\), 即 \\(f^{-1}(f(M)) \subset KM\\).

    综上, \\(f^{-1}(f(M)) = KM\\), 证毕.
