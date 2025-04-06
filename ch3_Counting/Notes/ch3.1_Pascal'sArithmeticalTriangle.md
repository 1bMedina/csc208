# Chapter 3.1 - Pascal's Arithmetical Triangle

## Definitions
- **Pascal's Triangle**: A triangle where every number in the triangle is the sum of the two numbers above it. 
    - The numbers in Pascal's triangle are often called **binomial coefficients** because of Binomial Theorem. 
- **Integer Lattice**: is the set of all points in the Cartesian plane for which both $x$ and $y$ coordinates are integers. 
    - When drawing graphs on paper, the lattice is the set of all the intersections of the grid lines. 
- **Lattice Path**: is one of the shortest possible paths connecting two points on the lattice, moving only horizontally and vertically. 
    - A paths' **length** is the number of steps taken. 
    - To list the paths you could:
        - Draw them out
        - List them as a string of directions such as $xxyyx$
        - Find the number of paths that start at $(0,0)$ and end at $(m,n)$, then find the number of paths to the point directly to the left of the endpoint $(m -1, n)$ and add the number of paths to the point directly below the endpoint $(m, n-1)$
    - The *length* of the path determines the *row* of pascals triangle, and the number of steps in the $y$ direction says how far into the triangle we are, the *column*.
    - We can view counting lattice paths as choosing $k$ out of $n$ things: of the $n$ steps on the path, we choose $k$ of them to be in the x-direction.
- **Binary Digits**: simply $0$ and $1$.
- **Bit String**: is a string of binary digits. 
    - Example: $1001$ $0$ $1111$
    - The number of bits in the string is the **length** of the string. 
    - The number of 1's in a bit string is the **weight** of the string. 
    - An $n$-bit string is a bit string of the length $n$. 
    - $B^n_k$ is the set of all $n$-bit strings of weight $k$.
        - Example: $B^2_3$ is the bit strings of $011$ ,$101$ and $110$
    - Can be taken from lattice paths (example: $yxxxy$ to $01110$)
    - The number of 5-bit stings of weight 3 is the sum of the number of 4-bit strings of weight 3 and the number of 4-bit strings of weight 2
        - In symbols: $|B^5_3| = |B^4_3| + |B^4_2|$
    - Can be thought of as: of the $n$ bits in the string, we choose $k$ of them to be 1's.

- **Subset**: of set $A$ is any set all of whoes elements are also in $A$.
    - Think of starting with the set $A$ and removing some, none, or all of its elements: the resulting set is a subset of $A$.
    - When we think of subsets from bit strings we can think if the bit in position $n$ is a 0 that means we do not include $n$ in our subset, if it's a 1, we do.
        - Example: $A = \set{1,2,3,4,5,6}$ for binary string $001101$, the subset would be $\set{3,4,6}$.
    - **Counting Subsets**: The number of $k$-element subsets of a set with $n$ elements is the number in row $n$, column $K$ of Pascal's triangle: $n \choose k$, which we read as "$n$ choose $k$". This is the number of ways to choose $k$ items from a collection of $n$ items. 

## Theorems
- **Binomial Theorem**: The $n \text{th}$ row of Pascal's triangle gives the coefficients of the expansion of $(x+y)^n$. That is, for any positive integer $n$, 

```math
(x + y)^n = \binom{n}{0}x^n + \binom{n}{1}x^{n-1}y + ... + \binom{n}{n-1}xy^{n-1} + \binom{n}{n}y^n.,
```
- So the coefficient of $x^ky^n-k$ is $n \choose k$
## Notation
- Rows in Pascal's triangle are counted down starting at zero
- The columns are counted in from the left, also starting at zero
- The entry row $n$ and column $k$ will be denoted $n \choose k$
    - Pronounce $n \choose k$ as "$n$ **choose** $k$"