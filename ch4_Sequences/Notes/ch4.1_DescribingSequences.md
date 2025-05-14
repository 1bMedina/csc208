# Chapter 4.1 Describing Sequences 

## Notes
- Given any sequence $(a_n)_{n\in\N}$, we can always form a new sequence $(b_n)_{n\in\N}$ by 

$b_n = a_0 +a_1 + a_2 +...+a_n$

- Since the terms of $(b_n)$ are the sums of the initial part of the sequence $(a_n)$, we call  $(b_n)$ the **sequence of partial sums of** $(a_n)$.\
- To simplify writing out these sums, we often use the notation $\sum_{k=1} ^{n} a_k$. This means add up all the $a_k$'s where $k$ changes from $1$ to $n$.

## Definitions
- **Sequence**: Simply an ordered list of numbers. 
    - The order of the numbers is an essential characteristic of the sequence.
    - Variables are used to represent terms: $a_1, a_2, a_3, a_4,...$
        - The numbers in the subscripts are called ***indices*** (the plural of ***index***).
    - Really just a type of function. 

- **Closed Formula**: A ***closed formula*** for a sequence $(a_n)_{n \in \N}$ is a formula for $a_n$ using a fixed finite number of operations on $n$. 
    - This is what you normally think of as a formula in $n$, just as if you were defining a function in terms of $n$ (because that is exactly what you are doing).

- **Recursive Definition**: A ***recursive definition*** (sometimes called an ***inductive definition***) for a sequence $(a_n)_{n\in\N}$ consists of a ***recurrence relation*** : an equation relating a term of the sequence to previous terms (terms with smaller index), and an ***initial condition***: a list of a few terms of the sequence (one less than the number of terms in the recurrence relation). 

## Common Sequences
- $1,4,9,16,25,...$
    - The **square numbers**. The sequence $(s_n)_{n\geq1}$ has closed formula $s_n = n^2$
- $1,3,6,10,15,21,...$
    - The **triangular numbers**. The sequence $(T_n)_{n\geq1}$ has a closed formula $T_n = \frac{n(n+1)}{2}$.
- $1,2,4,8,16,32,...$
    - The **powers of 2**. The sequence $(a_n)_{n\geq0}$ with closed formula $a_n = 2^n$.
- $1,1,2,3,5,8,13,...$
    - The **Fibonacci numbers** (or Fibonacci sequence), defined recursively by $F_n = F_{n-1} + F_{n-2} \text{ with } F_1 = F_2 = 1$