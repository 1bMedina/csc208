# Chapter 2.3 - Planar Graphs

## Notes
- The relationship between the number of vertices, the number of edges, and the number of faces is called Euler's formula. 
- Creating a new 'spike' is when you add a new vertex connected by a new edge to a part of your graph.
- Completing a circuit is when you connect two vertices already in the graph with a new edge. 
- When adding a spike, the number of vertices and edges stay the same, and the number of faces remains the same meaning that $v-e+f=2$ stays the same.
- Completing the circuit adds one edge and face but keeps the vertices the same meaning that $v-e+f=2$ doesn't change again.
    - You can build any graph using this combination and $v-e+f=2$ will not change
- The **minimal criminal argument** is where we start with a minimal connected planar graph that does not satisfy the formula, then remove either an edge or a vertex (and its edge) to get a smaller connected planar graph that does satisfy the formula
    - Removing an edge or vertex does not change the quantity of $v-e+f =2$.
- when we set $g$ as the smallest cycle in a graph, then for any planar graph we have $gf \le 2e$. When this disagrees with Euler's formula, we know the graph cannot be planar. 
- ***Every*** convex polyhedron can be projected onto the plane without edges crossing. 
- 

## Definitions
- **Polyhedron**: a geometric solid made up of flat polygonal faces joi9ned at edges and vertices. 
- **Convex Polyhedra**: where any line segment connecting two points on the interior of the polyhedron must be entirely contained inside the polyhedron.

## Theorems
- **Kuratowski's Theorem**: A graph is planar if and only if it does not contain a subgraph that is a subdivision of $K_5$ or $K_3,_3$.
- **Five Regular Theorem**: There are exactly five regular polyhedra. 

## Formulas
- **Euler's Formula for Planar Graphs**: For any connected planar graph with $v$ vertices, $e$ edges, and $f$ faces, we have:
    $$
    v - e + f = 2
    $$

