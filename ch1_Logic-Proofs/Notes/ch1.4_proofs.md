# Chapter 1.4 - Proofs

## Direct Proofs
### Vocabulary
- **Mini Sudoku**: partially filled 4 x 4 grid of squares, divided into four 2 x 2 boxes where each box can be empty or contain a digit from 1 to 4.
    - It is **valid** when any digit 1 to 4 does not appear more than once in any row, column, or box.
    - The **solution** is a valid puzzle with no empty boxes and every non-empty squares of the puzzle unchanged. 
    - The mini sudoku is **solvable** if there is exactly one solution. 
    - **Proposition**: Any solution to a mini sudoku will have each digit from 1 to 4 appear exactly once in each row, column, and box, appearing a total of 4 times. 
- **Arbitrary Solution**: A solution chosen without any restrictions or conditions. 

### Notes 
- The direct proof for $P \to Q$ will roughly look like:
    
    Assume $P$. Explain, explain, ...explain. Therefore $Q$.

## Proof by Contrapositive
### Vocabulary
- **Proof by Contrapositive**: gives direct proof of the contrapositive of the implication.
    - This is enough as the contrapositive is logically equivalent to the original implication.

### Notes 
- The skeleton proof for $P \to Q$ by contrapositive will roughly look like:

    Assume $\neg Q$. Explain, Explain, ...explain. Therfore $\neg P$.

- Direct proofs and proofs by contrapositive can be used when proving **implications**. 

## Proof by Contradiction
### Vocabulary
- **Proof by Contradiction**: exploits the fact that the logic in an argument is faulty, or at least one assumption must be false. 
- 
### Notes 
- Start with a single conclusion and construct a valid proof that leads to a false conclusion. 
- The general format of a proof by contradiction to prove a statement $P$ looks like:

    Assume $\neg P$. This means that..., which tells us..., so we can say... But this is a contradiction, so $P$ must be true. 
    - This can be thought of a direct proof structured like:

        $\neg P \to$ contradiction.




