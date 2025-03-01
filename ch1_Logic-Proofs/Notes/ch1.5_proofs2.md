# Chapter 1.5 Proofs about Discrete Structures

## Vocabulary
- **Set**: an unordered collection of elements.
    - Example: $A = \set {1,2,3,4,5}$, or
    - $B = \set {x \in \N : x < 10}$
    - The second set is a set of natural numbers less than ten

- **Subset**: a set $A$ is a subset of set $B$, provided that every element of $A$ is also an element of $B$
    - Written as: $A \subseteq B$.

- **Superset**: set $B$ (in the case above) can sometimes be called a **superset** of $A$.

- **Proper Subset**: if every element of $A$ is an element in $B$, and there is at least one element in $B$ that is **not** in 
$A$.
    - Written as: $A \subset B$ 

- **Element Chasing Proof**: 
    - Example: For any sets $A$, $B$, and $C$, if $A \subseteq B$ and $B \subseteq C$, then $A \subseteq C$

- **Injective** (or **one-to-one**): provided every element in $B$ (in a $f : A \to B$ function) is the image of at most one element in A. 
    - No element of $B$ is the **output** of more than one **input** from $A$

- **Cardinality**: The number of elements in  a set (like set $A$).
    - $|A|$ denotes the cardinality of the set $A$.

- **Corollary**: When you apply a theorem or proposition to directly prove another result. 
    - Example: Suppose a class has 25 students. Then at least two students share the same birth month. 
        - Proof: The domain has 25 elements while the codomain only has 12, which indicates that the function is not injective. Therefore, at least 2 students share the same birth month. 

- Relation: on a set $A$ is a set of ordered pairs of elements from $A$.
    - Can be though of as a way to describe a type of relationship between elements of $A$

- Transitive: Whenever one thing is related to a second, and the second to a third, and then the first must also be related to the third. 
    - Example: If Alice is friends with Bob, then Bob is friends with Charlie, then Alice is also friends with Charlie. 
    - Can be written as: $x, y, z \in A$, if $xRy$ and $yRz$, then $xRz$

- **Degree**: is the number of edges that contain $v$, i.e., the number of edges **incident** to $v$
    - Let $v$ be the vertex in graph $G$.
    - Written $d(v)$

## Notes 
- A function $f : A \to B$ is a rule that assigns each element of the set $A$ (the domain) to exactly one element of set $B$ (the codomain).
    - It is any rule: there doesn't have to be a formula or rationale for it. 
- We use *two-line notation* to describe a function.
    - So $f: \set {1,2,3,4} \to \set {a,b,c,d}$ could be defined as

    $$
    f = (\begin{array}{cccc}1& 2&3 &4 \\a &b &c &d \end{array})
    $$

    - This indicates that at $f(1) = a$ and so on.

- Suppose $f : A \to B$ is a function with $A$ and $B$ both finite sets. If $|A| > |B|$, then $f$ is **not** injective.

- Functions always have inputs from a set (called the **domain**) and outputs in a set as well (called the **codomain**). 

- Given a function $f : X \to Y$ and a set $A \subseteq X$, we define the **image of $A$ under $f$** to be the set $f(A) = \set {f(a) \in Y : a \in A}$. 
    - That is, $f(A)$ is the set of all outputs of the function for inputs in $A$

- Let $f : X \to Y$ be a function, and let $A$ and $B$ be subests of $X$. If $A \subseteq B$, then $f(A) \subseteq f(B)$.

- A statement is true when the pair is in the relation. 
    - For example: the statement "3 is less than 5," us true because the pair $(3, 5)$ is in the relation $<$.
    - Can say a relation is just a predicate, where the variables come from the same set.

- Relations often have special symbols like $=$, or $\leq$ or $\perp$.
    - For a general relation we'll likely use $\sim$ or $x \sim y$, or we'll use uppercase letter like $R$ and write $R(x,y)$ or $xRy$ or even $(x,y) \in R$
        - These all mean the same thing
- Proving that a relation is not transitive takes nothing more than finding a counterexample, which means finding three elements $a, b,$ and $c$ such that $a \sim b$, $b \sim c$ but $a \nsim c$

- A **graph** is set $V$ of **vertices** and a set $E$ of **edges**. 
    - The edges are two-element subsets of the vertices, and we think of them as representing relationships between the vertices

- Graphs represent a type of relationship between elements (vertices), we can use graphs to represent many real-world problems.

- In any graph, the number of vertices with odd degree must be even.


