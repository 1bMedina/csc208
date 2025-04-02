# Chapter 2.6 - Relations and Graphs

## Definitions
- **Cartesian Product**: All possible ordered pairs from two sets. 
    - Written as $A \times B = \set{(a,b: a \in A, b \in B)}$.
    - Can be said as the set of all ordered pairs of elements from $A$ and $B$.
- **Binary Relation**: A binary relation is a set of ordered pairs. 
    - We say that a binary relation is a **relation on sets $A$ and $B$** provided the ordered pairs are a subset of $A \times B$
    - We say a binary relation is a **relation on set $A$** provided the ordered pairs are a subset of $A \times A$
        - $A \times A$ is just the set of all ordered pairs where both coordinates are elements from $A$.
- **Inverse Relation**: Given a binary relation $R$, define $R^{-1}$ to be the **inverse** of $R$ as the set $R^{-1} = \set{(b,a) : (a,b) \in R}$
- **Composition**: Let $R$ be a relation from set $a$ to $B$ and $S$ be a relation from $B$ to $C$. The **composition** of $R$ and $S$ is $R \circ S = \set{(a,c) \in A \times C: (a,b) \in R \text{ and } (b, c) \in S \text{ for some } b \in B}$
- Let $R$ be a relation on the set $A$. We say, 
    - $R$ is **reflective** provided $(a,a) \in A \text{ for all } a \in A$
    - $R$ is **symmetric** provided, for all $a,b \in A \text{ if } (a,b) \in R \text{ then } (b,a) \in R$
    - $R$ is **transitive** provided, for all $a,b,c \in A \text{ if } (a,b) \in R \text{ and } (b,c) \in R \text{ then } (a,c) \in R$
- **Equivalence Relation**: A relation that is reflective, symmetric, and transitive. 
    - *Example*: equality
- Let $R$ be a relation on the set $A$, and let $a$ be an element of $A$. The **relation class** of $a$, written $[a]$ is the set of all elements $b$ such that $(a, b) \in R$ (the set of $b$ that are related to $a$ by $R$). That is,

    ```math
    [a] = \{b \in A: (a, b) \in R\}.
    ```
    - When $R$ is an equivalence relation, we call the relation classes **equivalence classes**.

- **Partition**: Given a non-empty set $A$, a **partition** is a set $P$ of non-empty subsets of $A$ such that every element of $A$ is in exactly one element of $P$. 
    - A partition is a way to break up a set into *disjoint* subsets that *cover* the whole set. 
    - The subsets that are disjoint means no element is in *more than one* subset.
## Theorems
- **Equivalence Relation Forms Partition Theorem**: 
    - Given any equivalence relation $R$ on a set $A$, the equivalence classes form a partition of $A$.

    - Given any partition $P = \{B_1, B_2,...,\}$ of a set $A$, the relation $a \equiv_P b$ if and only if $a$ and $b$ belong to the same block of $P$, is an equivalence relation.

    - Further, the equivalence classes for the equivalence relation formed by a partition are exactly the original partition, and the equivalence relation built by the partition of its equivalence classes is exactly the original equivalence relation.