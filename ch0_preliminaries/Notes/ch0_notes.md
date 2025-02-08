# Notes - Chapter 0: Introduction and Preliminaries

## Vocabulary
- **Discrete (adj)**: individually separate and distinct

- **Mathematics**: The study of numbers, lines, functions, triangles, parallelepipeds, and vectors 

- **Discrete Structures**: the mathematical objects that we use to represent parts of the problems we are solving.

- **A Set**: an unordered collection of elements. 

- **Cardinality**: How many elements are in a set.

- **Function**: A rule that assigns each input to exactly one output.

- **Domain**: The set of all inputs.

- **Codomain**: The set of all allowable outputs.

- **Range**: The set of all actual outputs (could also be known as the set of all images of elements from the domain).

- **Closed Formula**: A formula where each output is given by an explicit rule based solely on its input. 

- **Recursive Definition**: Tells us how to compute the output for a given input based on other outputs of the function. 

- **Initial Condition**: Often given by $f(0)$.

- **Sequences**: An ordered list where the order matters. 

- **Finite Sequence**: A sequence with a specific number of elements.

- **Infinite Sequence**: A sequence that continues indefinitely.

- **Relations**: A way to describe the relationship between elements of one or more set. 

- **Binary Relations**: The relationship between two elements (ex: Less than $<$)

- **Irreflexive Relation**: A relation where no element is related to itself. 

- **Antisymmetric Relation**: A relation in which two elements of a set are only related to each other if they are equal. 

- **Transitive Relation**: Where if $a$ is related to $b$ and $b$ is related to $c$, then $a$ is also related to $c$.

- **Equivalence Relation**: When a relation is reflexive, symmetric, and transitive. 

- **Graphs**: A mathematical structure consisting of **vertices** (nodes) and **edges** (connections).

- **Vertices**: Individual points (or nodes) that make up a graph.

- **Edges**: A two-element subset of vertices. 

- **Symmetric**: If $a$ is related to $b$, then $b$ is related to $a$. 



## Discrete Structures
### Sets
- A set is an unordered collection of elements

- We use sets to be able to talk about collections of numbers and other topics which we collect. 

- Sets can be described by saying exactly what elements are members of the set.

- **Set comprehension** (aka **set builder notation**) can be used to describe sets. 

    - An example of set comprehension is: $A = \lbrace x \in \mathbb{N} : x < 10 \rbrace$

- We can build new sets from one we already have ny taking the **union** or **intersection** of sets

- **Cardinality** is how many elements are in a set. 

### Functions
- One definition for a **function** is a rule that assigns each input to exactly one output.

- The output can be called the **image** of the input.

- The function can come with a **domain** and a **codomain**. 

- There may also be the **range** of the function. 

- We write $f : X \rightarrow Y$ to describe that function f has a domain of X and a codomain of Y.

- A key thing about the function rule is that there is exactly one output for each input.

- The graph of a function is often described as a set of points.

### Sequences
- A **sequence** is a list of ordered elements where the order matters.

- There are **finite** and **infinite** sequences. 

- Sequences are often used as counting tools.

### Relations
- A **relation** is a way to describe the relationship between elements of one or more sets. 
    - Examples of relations: less that, multiple of, even or odd, not equal, etc.

- The examples above are **binary relations**. 

- Relations can have standard properties. 
    - By deciding whether a particular relation has a given property can often help understand the relation better.

- The less-than relationship is **irreflexive** because there are no elements that are less than themselves. 

- Less-than relationship is also **antisymmetric** since there are no distinct numbers $a$ and $b$ such that $a < b$ and $b < a$.

- It is also **transitive** since if $a < b$ and $b < c$ then it must follow that $a < c$.

- If we can prove a given relation is **reflexive**, **symmetric**, and **transitive**, then we know that the relation is an **equivalence relation**. 
    - Once known its a equivalence relation, its known that it has a bunch of other properties.

### Graphs
- A **graph** is a type of relation, one that is **symmetric** and **irreflexive**.

- Graphs are represented by **vertices** and **edges**.

- Examples:
    - **Geographical Graph**: Locations as vertices and shared borders as edges.
    - **Flight Network**: Airports as vertices and flights as edges. 

## Questions 
### What is discrete math?
{0,1,2,3} is discrete because the elements are separate. Whereas $y = x^2$ is not discrete because the outputs are not separate. 
### What are the four main topics that will be presented in this book?
The four main topics are **combinatorics** (the theory of ways things combine), **sequences**, **symbolic logic**, and **graph theory**.

### What are discrete structures? Which specific examples are listed in the chapter? 
Discrete structures are the mathematical objects that we use to represent parts of the problems we are solving. 
- Specific Examples:
    - **Sets**: An unordered collection of elements
    - **Functions**: A rule that assigns each input with exactly one output
    - **Sequences**: A list of ordered elements where order matters.
    - **Relations**: A way to describe the relationship between elements of one or more sets.
    - **Graphs**: A mathematical structure consisting of vertices and edges.