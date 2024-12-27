# Banach Fixed Point Theorem

`Definition (from Wikipedia)`: Let $(X, d)$ be a non-empty [complete metric space](./complete-metric-space.md) with a [contraction mapping](./contraction-mapping.md) $T: X \rightarrow X$. Then $T$ admits a unique fixed point $x^*$ in $X$ (i.e. $T(x^*)=x^*$). Furthermore, $x^*$ can be found as follows: 
1. Start with an arbitrary element $x_0 \in X$
2. Define a sequence $(x_n)_{n \in \N}$ such that $x_n = T(x_{n-1})$ for $n \geq 1$
3. Then, $\lim_{n\rightarrow \inf} x_n = x^*$


## Sources
- [x] https://en.wikipedia.org/wiki/Banach_fixed-point_theorem

## Supplementaries
1. In https://en.wikipedia.org/wiki/Banach_fixed-point_theorem check out:
   1. Lipschitz constant 
   2. Speed of convergence
   3. Proof
2. 

## More Information
- Stated first by Stefan Banach in 1922