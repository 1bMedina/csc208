# Chapter 3.5 - Counting Multisets
## Practice Problems 7 & Additional Problem 3 - Blu and Rehoboth

## Question 7:

> How many integer solutions to $x_1 +x_2 +x_3 +x_4 = 38$ are there for which $x_1 \geq 4, x_2 \geq 4, x_3 \geq 1, \text{and } x_4 \geq 1$?

**Answer**: $\boxed{31\choose3}$ or $\boxed{4495}$

**Why?** 
- First get the minimum required: $4+4+1+1 = 10$
    - This gives us $38-10=28$
- Now we have to distribute the leftovers, which means we need to split 28 into 4 separate categories (being $x_1,x_2...$)

Now imagine a row of 28 stones:

$\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ$

We need to divide them into 4 categories using 3 dividers

$\circ\circ\circ\circ|\circ\circ\circ\circ\circ\circ\circ|\circ\circ\circ\circ\circ\circ|\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ\circ$

This gives us $28$ stones + $3$ sticks $=31$
Therefore, we get $31\choose3$ because we to choose 3 positions out of the 31. 

## Additional Problem 3

> We have represented multisets with sticks and stones diagrams, then counted the number of sticks and stones diagrams to tell us the number of multisets. This is only a valid process if every multiset corresponds to exactly one sticks and stones diagram, and vice versa.

1. Clearly write down the rule for how to convert a multiset into a sticks and stones diagram. That is, describe the function $f$ that takes a multiset as input and outputs a sticks and stones diagram.
    - Step 1: 
        - You have $n$ items from $r$ fruits $\set{\text{Bananas, Apples, Oranges, Grapes,....}}$
            - Items can repeat $\set{\text{Bananas,Bananas, Bananas, Grapes,..}}$
            - The order doesn't matter $\set{\text{Apples, Grapes, Bananas, Oranges,...}}$ 
        - This is the definition of a multiset, also known as a combination with repetition
    - Step 2:
        - To represent this as a sticks and stones diagram, each selected fruit becomes a stone ($\circ$). The different fruit types are separated by sticks ($|$), which are the commas. So the number of stones in each section tells you how many of that fruit type was chosen.
        - You will have $r-1$ sticks. Where $r$ is the amount of different types of fruit you have, so:

        $\set{\text{Bananas, Apples, Oranges, Grapes,...}} \text{or} \set{\text{Apples, Bananas, Grapes, Oranges,...}}= \circ|\circ|\circ|\circ$

        and 

        $\set{\text{Bananas, Bananas, Bananas, Grapes,...}} = \circ\circ\circ|||\circ$
    - Step 3:
        - How many ways can we arrange $n$ items and $r-1$ sticks?
            - $n$ represents the fruits
            - While $r$ represents the type of fruit
        
        $\binom{n+r-1}{r-1}$ or $\binom{n+r-1}{n}$

2. Prove that the function $f$ is a bijection. That is, prove that every sticks and stones diagram corresponds to exactly one multiset, and vice versa.

    - To prove it is a bijection we must prove to things:
        - It's injective 
        - It's surjective
    - Injective means that there is a one to one mapping or $f(a) = f(b)$ then $a= b$
        - Meaning no two elements map to the same thing
    - Surjective means there is at least one element that hits everything in the co-domain
    - It's both:
        - Injectivity:
            - When making the stick and stones diagram, you're putting a specific amount of stones in each section
            If different multisets have the same diagram then that means they have the same number for each item, for example fruits
            - So it's impossible for two different multisets to create the same diagram
        - Surjectivity:
            - When making a diagram, every single one has to have $n$ amount of stones and $r-1$ sticks, where $r$ represents the number of different types of groups, in our case fruits.
            - So if you have a multiset then it must be able to turn into a sticks and stones diagram. 