# Chapter 2.4 - Euler Trail and Circuits

## Notes
- A walk in a graph is a sequence of vertices such that every vertex in the sequence is adjacent to the vertices before and after it in the sequence.
    - If the walk travels along every edge only once, it is called Euler trail (or walk or path).
    - If the start and ending vertices are the same, it's called Euler circuit.

- Conditions for Euler Trails:
    - Can't include a spike, a vertex of degree 1
        - you would get stuck at the vertex, it is a dead end, unless you start there, but then there can't be a circuit.
    - If a graph has an Euler trail and two vertices with odd degree, then the trail must start at one of the odd degree vertices and end at the other. 
    - For a graph to have a circuit, all vertices must have an even degree. 

- A graph that visits every vertex exactly once is called a Hamilton path. 
    - There are also Hamilton cycles, which are Hamilton paths that start and stop at the same vertex.
- 


## Euler Trails and Circuits
- A graph has an Euler circuit if and only if the degree of every vertex is even.
- A graph has an Euler trail if and only if there are at most two vertices with odd degree.
