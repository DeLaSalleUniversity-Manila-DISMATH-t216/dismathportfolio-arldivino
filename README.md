# dismathportfolio-arldivino
dismathportfolio-arldivino created by Classroom for GitHub

##Week 1
- Discrete Mathematics(DISMATH) was explained to us, and what it is for
- A proposition could be either true or false, but not both.
- Different operators and their logical equation/use. 

| Logical Symbol  |  Logical Operator     | Shorthand | Formula                                       | Logical Expression             |
| :-------------: |:---------------------:|:---------:|:---------------------------------------------:|:-----------------------------:|
| ¬               | Negation              | not       | val(¬p) = 1 - val(p)                          | ¬p                           |
| ∧               | Conjunction           | and       | val(p ∧ q) = min(val(p), val(q))              | p ∧ q                          
| v               | Disjunction           | or        | val(p v q) = max(val(p), val(q))              | p v q                        |
| ⊕              | Exclusive disjunction | xor       | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| →               | Conditional           | if, then  | if val(p)  ≤ val(q) = 1 , otherwise  0        | p → q ≡  ¬p v q              |
| ↔               | Biconditional         | iff       | if val(p) equals val(q) = 1 , otherwise  0    |  p ↔ q ≡ (p → q) ∧ (q → p)    |

- Truth tables (rows = 2^n; n=number of variables)

##Week 2
- Logical equivalences

|                           Equivalence                           |         Name        |
|:-------------------------------------------------------------:  |:-------------------:|
|                      p ∧ T ≡ p <br> p v F ≡ p                   |    Identity laws    |
|                       p v T ≡ T <br> p ∧ F ≡ F                  |   Domination laws   |
|                       p v p ≡ p <br> p ∧ p ≡ p                  |   Idempotent laws   |
|                            ¬(¬p) ≡ p                            | Double negation law |
|                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p              |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                   |    Negation laws    |
- Statement verifying using logical equivalences
- Predicate and Subject use for simplifying statements for verification.
- Quantifiers:Universal and Existential Quantifiers.

##Week 3

- Application of Fallacies to DISMATH. 
- Rules of inference for simpler(faster/shorter) proving vs. truth tables

|   Rule of Inference       |            Tautology           |          Name          |
|:--------------------:     |:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |      Modus ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus tollens     |
|     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical syllogism |
|      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive syllogism |
|       p<br>∴p ∨ q         |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴p         |           (p ∧ q) → p          |      Simplication      |
|      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       |
- Direct Proof

##Week 4

- Proof by Contraposition
- Vacuous Proof
- Proof by Contradiction

##Week 5

- Counterexamples
- Mathematical Induction
- Proof by equivalences

##Week 6
- Program Correctness
- Recursive Algorithms
- Summation

##Week 7
- Set theory
- Functions
- Different Types of functions

##Week 8
- Algorithms
- Pseudocodes

##Week 9
- Searching Algorithms
- Sorting Algorithms
- Greedy Algorithms

##Week 10
- Big O-Notations
- Big Omega Notations and Big Theta Notations
- Algorithm time comlpexity

##Week 11
- Graph Theory
- Handshaking Theorem
- Euler Circuit and Euler Paths
- Hamiltonian Path and Hamiltionian Circuits
- Planar Graphs

##Week 12
- Graph Coloring
- Trees
- Statement Tables
