# Chapter 2.2 - Trees 

## Notes:
- **Rooted trees** are where we simply designate one vertex as the root. 
- A **spanning tree** is a tree that includes all the vertices of a connected graph. 
- A **minimum spanning tree** is a spanning tree that has the smallest possible combined weight.
    - Finding the minimum spanning tree uses basically the same algorithms as we described above, but when picking an edge to add, you always pick the smallest,
- As soon as one vertex of a tree is designated as the ***root***, then every other vertex on the tree can be characterized by its position relative to the root. 
- If two vertices are adjacent, then we say one of them is the ***parent*** of the other, which is called the ***child*** of the parent.
- All non-root vertices have exactly one parent
- Generally we say that a vertex $v$ is a descendent of a vertex $u$ provided $u$ is a vertex on the bath from $v$ to the root.
    - Then we would call $u$ an ancestor of $v$
- Vertices $v$ and $u$ are called siblings provided they have the same parent. 
    - Siblings are never adjacent.
- A **breadth-first search** is usually when you chose to visit all vertices in the same generation before any vertices of the next generation. 
- A **depth-first search** is when we travel as far from the root as fast as possible, then backtrack until we can move forward again. 


## Propositions:
- **Alternate definition for tree**: A graph $T$ is a tree if and only if between every pair of distinct vertices of $T$ there is a unique path.

- **Trees have leaves**: Any tree with at least 2 vertices has at least 2 vertices of degree one. 

- **Tree with edges**: Let $T$ be a tree with $v$ vertices and $e$ edges. Then $e = v - 1$



## Corollary:
A graph $F$ is a for3est if and only if between any pair of vertices in $F$ there is at most one path.

## Definitions:
- **Trees and Forests**: A Tree is a connected graph containing no cycles. A forest is a graph containing no cycles. 
    - This means that a connected forest is a tree.

- **Spanning tree**: Given a connected graph $G$, a **spanning tree** of $G$ is a subgraph of $G$ which is a tree and includes all vertices of $G$.

## Theorems
- Every connected graph has a spanning tree.

