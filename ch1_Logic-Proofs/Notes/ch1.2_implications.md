# Chapter 1.2 - Implications

## Vocabulary
- **Implication** (or **conditional**) - is a molecular statement of the form $P \to Q$

    - $P$ and $Q$ are statements 

        - $P$ is the **hypothesis** (or **antecedent**)

        - $Q$ is the **conclusion** (or **consequent**)

    - An implication is **true** provided $P$ is **false** or $Q$ is true (or both), and false otherwise. 

    - The only way for $P \to Q$ to be false is for $P$ to be true **and** $Q$ false.
- "$P$ is necessary for $Q$" means $Q \to P$
- "$P$ is sufficient for $Q$" means $P \to Q$
- If $P$ is necessary and sufficient for $Q$, then $P \leftrightarrow Q$

## Notes
- The definition of an implication can be represented as a truth table 

- The only way for an implication to be false is for the hypothesis to be true and the conclusion false.

- An implication is a way of expressing a relationship between two statements

- The **converse** of $P \to Q$ is $Q \to P$

- The **contrapositive** of $P \to Q$ is $\neg Q \to \neg P$

- The **inverse** of $P \to Q$ is $\neg P \to \neg Q$

- The converse and contrapositive both switch the order of the two statements

- When considering statements with quantifiers, we ignore the outside quantifiers when forming converse, contrapositive, and inverse

    - A quantified implication $\forall x (P(x) \to Q(x))$ has: 

        - **Converse**: $\forall x (Q(x) \to P(x))$

        - **Contrapositive**: $\forall x (\neg Q(x) \to \neg P(x))$

        - **Inverse**: $\forall x (\neg P(x) \to \neg Q(x))$

    - It is unlikely we will encounter a statement like $\exists x (P(x) \to Q(x))$ because it would automatically be true if there was any $x$ that made $P(x)$ false.

- **The contrapositive of a true statement is always true**

- When $P \to Q$ and $Q \to P$ we write $P \leftrightarrow Q$

- If and only if statements can be thought to have 2 parts: an implication and its converse


