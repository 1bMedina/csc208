# Chapter 3.4 - Combinations and Permutations

## Theorems
- **Permutations of $n$ Elements**: There are $n! = n \cdot (n-1)\cdot(n-2).....2\cdot1$ permutations of $n$ (distinct) elements.

- **$k$-permutation of $n$ elements**: The number of $k$-permutations of $n$ elements is 
<br>

$P(n,k) = \dfrac{n!}{(n-k)!} =n(n-1)(n-2)...(n-(k-1)).$

<br>

- When $n = k$ we have $P(n,n) = \dfrac{n!}{(n-n)!}=n!$ (since we defined $0!$ to be $1$)

- **Closed Formula for ${n}\choose {k}$**: 
<br>

${n\choose k} = \dfrac{n!}{(n-k)!k!} = \dfrac{n(n-1)(n-2)...(n-(k-1))}{k(k-1)(k-2)...1}$


<br>



## Definitions
- **Permutation**: is a (possible) rearrangement of objects.
    - Each permutation is really a *sequence* or a *tuple* of fixed length
    - If we are counting sequences

- **Bijective**: Where a function is both *injective* (one-to-one) and surjective (onto).
    - **Injective**: No two inputs share the same output
    - **Surjective**: Every possible output is matched with some input

- **$k$-permutation of $n$ elements**: $P(n,k)$ is the number of **$k$-permutations of $n$ elements**, the number of ways to **arrange** $k$ objects chosen from $n$ distinct objects. 
    - We must apply the multiplicative principle to $k$ numbers, starting with $n$ and counting backwards. For example, $P(10,4) = 10 \cdot 9 \cdot 8 \cdot 7$ 

- **Combinations**: Another name for the collection of things ${n\choose k}$ counts.
    - If we are counting sets

## Principles
- **Multiplicative Principle**: given $abc$ we have 3 choices for slot one, 2 choices for slot two, and 1 choice for slot three therefore, we have $3\cdot2\cdot1$ by the multiplicative principle



## Notation: 
- $n!$ is read as " $n$ factorial"
    - Is the product of all positive integers less than or equal to $n$ (for convenience, we also define $0!$ to be $1$)



