# Chapter 1.3 - Rules of Logic

## Vocabulary
- **Tautology**: A statement that is necessarily true based on its logical form alone. 
- **Logically Equivalent**: When statements are either both true or both false.
    - When $P$ is true precisely when $Q$ is true is logical equivalence. 
    - Ex: $\neg P \lor Q$ and $P \to Q$
    - Written as $P \equiv Q$
- **Deduction Rule**: an argument form that is always valid. 
- Two statements are logically equivalent provided that in every row of the truth table in which the first statement is true, so is the second, and in every row which the second statement is true, so is the first.


## Notes
- Logic does not care about the context of atomic statements or the meaning of the predicates.
- It's a good idea to separate the content from the logical form of arguments. 
- You can use a **truth table** to keep track of all the possibilities 
- To check is two statements are logically equivalent, you can create a truth table and check whether the columns for the two statements are identical
- Every implication can be written as a disjunction
- To verify if two statements are logically equivalent you can use truth tables or a sequence of logically equivalent replacements
- You can do double negation. For example: $\neg \neg P \equiv P$
- You can have 2 statements involving quantifiers and predicates be logically equivalent
- Sometimes quantifiers can have nothing to do with the equivalence 
- Sometimes the quantifiers are what make a statement logically equivalent 
- Negating an existential quantifier results in a universal quantifier
- $\neg \forall x P(x)$ is equivalent to $\exists x \neg P(x)$
- $\neg \exists x P(x)$ is equivalent to $\forall x \neg P(x)$
- Universal quantifiers are like conjunctions
- Existential quantifiers are like disjunctions
- Predicate logic extends propositional logic
- 

## Theorem
- An implication is logically equivalent to its contrapositive. For example, $P \to Q \equiv \neg Q \to \neg P$
    - For the **proof**, you just examine the truth tables. 
- **De Morgan's Laws**:
    - The negation of a disjunction or conjunction is logically equivalent to a conjunction or a disjunction of negations, respectively. For example:

    $\neg (P \land Q) \equiv \neg P \lor \neg Q$

    and, 

    $\neg (P \lor Q) \equiv \neg P \land \neg Q$
- Negation of an Implication:
    - The negation of an implication is a conjunction:

    $\neg (P \to Q) \equiv P \land \neg Q$

    - The only way for an implication to be false is for the hypothesis to be true **and** the conclusion to be false.
