# Chapter 2.5 - Coloring

## Notes:
- $K_n$ has a chromatic number $n$
- there is an upper bound to the number of colors needed for any map
-  for every graph $G$, the chromatic number of $G$ is at least 1 and at most the number of vertices of $G$.
- **Clique**: a set of vertices all of which are pairwise adjacent.
    - $n$ is just a copy of the complete graph $K_n$
- We define the clique number of a graph to be the largest $n$ for which the graph contains a clique of size .
- Any clique of size $n$ cannot be colored with fewer than $n$ colors, so we have a nice lower bound
- Graphs are perfect when the clique number is equal to the chromatic number

- The least number of colors required to properly color the edges of a graph $G$ is called the **chromatic index** of $G$, written $\chi'(G)$



## Theorem:
- **The Four Color Theorem**: If $G$ is a planar graph, then the chromatic number of $G$ is less than or equal to 4. Thus any map can properly be colored with 4 or few colors.

- **Clique Number Theorem**: The chromatic number of a graph $G$ is at least the clique number of $G$

- **Brooks' Theorem**: Any graph $G$ that satisfies $\chi(G) \le \Delta (G)$, unless $G$ is a complete graph or an odd cycle, in which case $\chi(G) = \Delta(G)+1$

- **Vizing's Theorem**: For any graph $G$, the chromatic index $\chi'(G)$ is either $\Delta(G)$ or $\Delta(G)+1$