# Bellman-Ford Algorithm: An Efficient Improvement Using the Yen-BF Technique

Poster presentation for the **Advanced Algorithm** course, Department of Computer Science and Engineering, **Southeast University**.

**Authors:** Fouzia Hoque (2023100000579) · MD. Emon Rana (2023100000645)

📄 Poster: [Bellman_Ford_Yen_BF_Poster.pdf](Bellman_Ford_Yen_BF_Poster.pdf)

## About

The Bellman-Ford algorithm finds single-source shortest paths in directed graphs with negative edge weights and detects negative-weight cycles, but it converges slowly. The Yen-BF improvement (Jin Y. Yen, 1970) runs a forward and a backward scan of the edge list in each relaxation pass, so distance improvements propagate in both directions at once — roughly halving the number of iterations in practice, while the worst case stays O(V·E).

## What the poster covers

- Algorithm overview and step-by-step pseudocode for Bellman-Ford and Yen-BF
- Mathematical formulation: DP recurrence, relaxation condition, negative-cycle detection
- Time and space complexity analysis, including the Yen-BF convergence bound
- Comparison table: Bellman-Ford vs Yen-BF vs Dijkstra's vs SPFA
- Case study on a 6-vertex graph (S, A, B, C, D, T) with a detailed iteration table — final distances S=0, A=4, B=2, C=7, D=7, T=5; shortest path to T: S → B → D → T (cost 5)
- Real-world applications: RIP network routing, currency arbitrage detection, GPS routing with tolls and penalties

## References

1. R. Bellman, "On a routing problem", *Quarterly of Applied Mathematics*, 16(1), 1958.
2. T. H. Cormen et al., *Introduction to Algorithms*, MIT Press, 4th ed., 2022.
3. L. R. Ford, "Network flow theory", RAND Corporation, 1956.
4. E. F. Moore, "The shortest path through a maze", *Proc. Int. Symp. on the Theory of Switching*, Harvard University Press, 1959.
5. J. Y. Yen, "An algorithm for finding shortest routes from all source nodes to a given destination in general networks", *Quarterly of Applied Mathematics*, 27(4), 1970.
