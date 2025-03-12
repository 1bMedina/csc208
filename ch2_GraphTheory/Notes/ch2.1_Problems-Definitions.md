# Chapter 2.1 - Problems and Definitions

## Notes
- **Graphs** are made up of a collection of dots, called **vertices**, and lines connection those dots, called **edges**. 
    - When two vertices are connected by an edge, we say they are **adjacent**.
- An **adjacency list** is a list where each vertex gets a list of which other vertices it's adjacent to.
- An **adjacency matrix** is here there are rows and columns that correspond to the vertices and the entries are 1 if the vertices are adjacent to 0 otherwise.
- A graph could be defined as $(\set{a,b,c,d}, \set{\set{a,b}, \set{b,c},\set{b,d},\set{c,d}})$ 
    - Here we have four vertices (the letters $a,b,c,d$) and five edges (the pairs $\set{a,b}, \set{b,c},\set{b,d},\set{c,d}$).
- Graphs that are basically the same, but perhaps not equal, are called **isomorphic**.
    - Graphs can be isomorphic if they are the same except for the name of the vertices. 
- An isomorphism is simply a function which renames the vertices.
- A collection of isomorphic graphs are often called an **isomorphism class**.
- Every induced subgraph is also an ordinary subgraph, but not conversely.
- Think of a subgraph as the result of deleting some vertices and edges from the larger graph.
- A **multigraph** is a graph when we want to consider double or more edges and single-edge loops.
- Graphs are **connected** when you can get from any vertex to any other vertex by following some path of edges
    - A graph that is not connected can be though of as two separate graphs drawn close together. 
- A graph is **complete** if every pair of vertices is connected by an edge. 
- $K_n$ is the complete graph on $n$ vertices.
- Each vertex in $K_n$ is adjacent to $n - 1$ other vertices. 
    - We call the number of edges emanating from a given vertex the **degree** of that vertex. 
- The sum of the degrees of all vertices will always be twice the number of edges, since each edge adds to the degree of two vertices.
    - The sum of the degrees of all vertices in any graph must be even.

## Definitions
- ***Graph***: A **graph** is an ordered pair $G = (V, E)$ consisting of a nonempty set $V$ (called the **vertices**) and set $E$ (called the **edges**) of two-element subsets of $V$.
- ***Isomorphism***: An **isomorphism** between two graphs $G_1$ and $G_2$ is a bijection $f: V_1 \to V_2$ between the vertices of the graph such that $\set {a,b}$ is an edge in $G_1$ if and only if $\set{f(a), f(b)}$ is an edge in $G_2$
    - Two graphs are **isomorphic** if there is an isomorphism between them. In this case we write $G_1 \cong G_2$.
- ***Subgraphs***: We say that $G'=(V', E')$ is a **subgraph** of $G=(V,E)$, and write $G' \subseteq G$, provided $V' \subseteq V$ and $E' \subseteq E$
    - We say that $G'=(V', E')$ is an **induced subgraph** of $G=(V,E)$ provided $V' \subseteq V$ and every edge in $E$ whose vertices are still in $V'$ is also an edge in $E'$.
- ***Bipartite***: We say a graph is bipartite if the vertices can be divided into 2 sets, $A$ and $B$, with no two vertices in $A$ adjacent and no two vertices in $B$ adjacent.

## Lemma 
- ***Handshake Lemma***: In any graph, the sum of the degrees of vertices in the graph is always twice the number of edges. 
    - Handshake lemma is sometimes called the *degree sum formula* and can be written symbolically as:
    $$\sum\limits_{v\in V} d(v)=2e.
    $$
    - The notation $d(v)$ stands for the degree of the vertex $v$.
    - One use for the lemma is to actually find the number of edges in a graph.
        - To do so you must be given the degree sequence for the graph (or be able to find it from other information).

## Proposition
- In any graph, the number of vertices with odd degree must be even. 
