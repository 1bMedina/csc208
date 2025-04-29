# Chapter 3.4 - Combinations and Permutations
## Practice Problems 4 & 9 - Blu and Hisham

## Question 4: 

> In an attempt to clean up your room, you have purchased a new floating shelf to put some of your 18 books you have stacked in a corner. These books are all by different authors. The new book shelf is large enough to hold 14 of the books. Careful: Before answering the next two questions, ask yourself which answer should be larger.


1. How many ways can you select and arrange 14 of the 18 books on the shelf? Notice that here we will allow the books to end up in any order.

    **Answer**: $\boxed{P(18,14)}$ 

    **Why?**: The order you put the books in matters as $a,b,c \neq c,b,a$ therefore we know it is a permutation problem not combinations. You are choosing $14$ ($k$) books from $18$ ($n$) books to arrange on the shelf in a specific order. So using the formula $P(n,k)$ we get $P(18,14)$.

2. How many ways can you arrange 14 of the 18 books on the shelf if you insist they must be arranged alphabetically by author?

    **Answer**: $\boxed{3060}$

    **Why?** The order of the books (alphabetical) is predetermined, and it is fixed, therefore order doesn't matter making this a combination problem. From there we can use:
    <br>
    $C(n,k) = \dfrac{n!}{(n-k)!k!}$
    <br>
    <br>
    $C(18,14) = \dfrac{18!}{4!14!} = \dfrac{18\cdot17\cdot16\cdot15}{4\cdot3\cdot2\cdot1}= \boxed{3060}$


## Question 9: 

> How many different seating arrangements are possible for King Arthur and his 16 knights around their round table?

**Answer**: $\boxed{16!}$

**Why?**: The order you put the knights in matters, again $a,b,c \neq c,b,a$, therefore it is a permutation problem. Then, it is a circular arrangement permutation so in order to calculate the number of ways to arrange people you need to use the formula $(n-1!)$. We use $(n-1)!$ instead of $n!$ because if you rotate a circular arrangement, it doesn't count as a new seating arrangement, which means we need to fix one person's position (the King) to break the rotational symmetry. There are $16$ knights + $1$ King $=$ to $17$ people at the table. Therefore, you need to do $(17-1)! = 16!$ to get all the possible seating arrangements.
