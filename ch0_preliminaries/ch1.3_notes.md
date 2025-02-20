# 1.3 Rules of Logic  

## Section Preview  
- Logic studies the way logical statements can interact with each other.  
- Implications are when one idea leads to another.  
- Implications are a good way to reduce the complexity of a problem without performing much math.  
- The main way to establish relationships between objects is through truth tables.  

## Truth Tables  
- As long as the second part of the implication is true, the return is true, regardless of whether the first part is true or false.  
- Analyze the statement:  
  > "If you get more doubles than any other player, then you will lose, or if you lose, then you must have bought the most properties,"  
  using truth tables.  

### Truth Table Example  
$
\begin{array}{|c|c|c||c|c|c||c|}
\hline
D & L & P & D \rightarrow L & L \rightarrow P & (D \rightarrow L) \lor (L \rightarrow P) \\
\hline
T & T & T & T & T & T \\
T & T & F & T & F & T \\
T & F & T & F & T & T \\
T & F & F & F & T & T \\
F & T & T & T & T & T \\
F & T & F & T & F & T \\
F & F & T & T & T & T \\
F & F & F & T & T & T \\
\hline
\end{array}
$

## Logical Equivalence  
- Logical equivalent statements are statements that are always either both true or both false.  
- Using truth tables can provide insight into a mathematical statement, allowing us to more easily refute it.  
- **De Morgan’s Laws**: The negation of a disjunction or conjunction is logically equivalent to a conjunction or disjunction of negations, respectively.  
- Every implication can be written as a disjunction.  

## Equivalence for Quantified Statements  
- A quantified statement is a logical expression that uses quantifiers to specify how many instances in a set have a certain property.  
- To dispute a universal claim, you need just a single counterexample.  
- Negating an existential quantifier results in a universal quantifier.  

## Deductions  
- The deduction rule is a fundamental principle in propositional logic that allows for deriving conclusions from given premises.  
- Deduction works when both values being true lead to a true statement.  
- Quantifier deductions also exist, but they cannot be proven with a truth table.  
## Theorems
* logically equivalent to its contrapositive: $P \implies Q \equiv \neg Q \implies \neg P\text{.}$
* De Morgan’s Laws: $\neg(P \wedge Q) \equiv \neg P \vee \neg Q$ and $\neg(P \vee Q) \equiv \neg P \wedge \neg Q\text{.}$
* Implications are Disjunctions: $P \implies Q \equiv \neg P \vee Q\text{.}$
* Negation of an Implication: $\neg(P \implies Q) \equiv P \wedge \neg Q\text{.}$