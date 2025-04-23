# Chapter 3.3 Non-Disjoint Outcomes 
## Practice Problems 1 & 2 - Blu Medina & Alex Elliott

## Question 1:
Suppose you have sets $A$ and $B$ with $|A| = 11$ and $|B| = 19$. 

**1. What is the largest possible value for $|A \cap B|$?**

**Answer:** 11
<br>

**Why?** The intersection ($\cap$) cannot exceed the size of the smaller set. Since $|A| = 11$, the largest possible $|A \cap B|$ is $11$ (i.e., $A$ is entirely contained within $B$)

**2. What is the smallest possible value for $|A \cap B|$?**

**Answer:** 0
<br>

**Why?** The intersection ($\cap$) can be empty if $A$ and $B$ are **disjoint** (no overlap). Therefore, the smallest possible $|A \cap B|$ is $0$.

**3. What are the possible values for $|A \cup B|$?**

**Answer:** $19 \leq |A \cup B| \leq 30$
<br>

**Why?** 
<br>

- The minimum union ($|A \cup B| = 19$)occurs when $A$ is entirely contained in $B$, the max intersection $|A \cap B| = 11.$
<br>
    ``` math
    |A \cup B| = 11 + 19 - 11 = 19
    ``` 
    Inclusion-Exclusion Principle
<br>

- The maximum union ($|A \cup B| =30$) occurs when $A$ and $B$ are disjoint, the minimum intersection $|A \cup B| = 11 + 19 - 0 = 30$

## Question 2:

If $|A| = 7$ and $|B| = 11$, what is $|A \cup B| + |A \cap B|$

**Answer:** 18
<br>

**Why?** The question doesn't specifically state that there are shared elements, therefore we assume there are no shared elements. Then we can write $|A \cup B|$ as $7+11$, and $|A \cap B| = 0$. Finally, we have $7+11+0=18$