# Complete Metric Space

`Definition (wikipedia):` A metric space $(X, d)$ is complete if any of the following equivalent conditions are satisfied.
1. Every Cauchy sequence of the points in $X$ also has its limit in $X$
2. Every Cauchy sequence in $X$ converges in $X$ 
3. Every decreasing sequence of non-empty closed subsets of $X$, with diameters tending to $0$, has a non-empty [intersection](https://en.wikipedia.org/wiki/Intersection_(set_theory)): if $F_n$ is closed and non-empty, $F_{n+1} \subseteq F_n$ for every $n$, and $diam(F_n) \rightarrow 0$, then there is a unique point $x \in X$ common to all sets $F_n$