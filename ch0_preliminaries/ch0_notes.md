# Chapter One Notes

## What is Discrete Math?

- The definition of discrete math is hard to define because the definition of mathematics itself is broad. However, discrete math can generally be understood as "separated" mathematics, dealing with countable, distinct elements rather than continuous ones.
- The interval \([0,\infty)\) is not discrete because it includes all real numbers from 0 onward, making it continuous rather than separated.
- A range of numbers that is not an interval is discrete. For example, \(\{1,2,3,4,5\}\) is discrete because the elements are distinct and separate from one another.
- The purpose of learning discrete math is to study mathematical structures that model real-world problems effectively.

## What are the four main topics in the book according to Professor Levin?

1. **Combinatorics** - The theory of ways things combine, particularly how to count these ways.
2. **Sequences** - Ordered lists of elements, often following specific rules or patterns.
3. **Symbolic Logic** - The study of formal logical systems and their applications.
4. **Graph Theory** - The study of graphs, which are mathematical structures used to model pairwise relations.

## What are Discrete Structures?

- Discrete structures are mathematical objects used to represent parts of problems being solved in discrete math.

### Sets

- A **set** is an unordered collection of elements.
- To define a set, one must specify exactly which elements are members.
- **Set comprehension** (also known as set-builder notation) is a way to define sets using conditions. An example of this is:
  \(S = \{ x \in \mathbb{N} \mid x < 10 \}\)
  This means \(S\) is the set of all natural numbers less than 10.
- The natural numbers \(\mathbb{N}\) are typically defined as \(\{0,1,2,3,\dots\}\), though some definitions start at 1.
- Sets are determined by their elements, not by order or repetition. For example:
  \(\{1,2,3,4,5\} = \{5,4,3,2,1\}\)
- Operations on sets include union, intersection, subsets, and finding cardinality (the number of elements in a set).

### Functions

- A **function** is a rule that assigns each input exactly one output.
- A function has:
    - A **domain** (the set of allowable inputs)
    - A **codomain** (the set of allowable outputs)
    - A **range** (the actual outputs produced by the function)
- Functions can be defined using:
    - Formulas (e.g., \(f(x) = x^2\))
    - Words (e.g., "square each input")
    - Tables or graphs
- A function must have only one output for each input.
- A function can also be represented as a set of ordered pairs.

### Sequences

- A **sequence** is an ordered list of elements.
- Sequences can be finite or infinite.
- The difference between sets and sequences:
    - A set does not care about order: \(\{1,2,3\} = \{3,2,1\}\).
    - A sequence does care about order: \((1,2,3) \neq (3,2,1)\).
- Sequences can be defined using:
    - A **closed formula** (e.g., \(a_n = 2n + 1\)).
    - A **recursive definition**, where each term is defined in terms of previous ones (e.g., Fibonacci sequence).

### Relations

- A **relation** is a connection between elements of one set and elements of another set (or the same set).
- Relations can be represented as sets of ordered pairs.
- Examples of relations:
    - "Less than" relation: \((2,5)\) belongs to the relation because \(2 < 5\).
    - "Divisibility" relation: \((4,2)\) belongs to the relation because \(4\) is divisible by \(2\).
- Relations can have properties such as:
    - **Reflexive**: If \(aRa\) for all \(a\).
    - **Symmetric**: If \(aRb\) implies \(bRa\).
    - **Transitive**: If \(aRb\) and \(bRc\), then \(aRc\).

### Graphs

- A **graph** consists of a set of **vertices** (or nodes) and a set of **edges** (connections between vertices).
- Graphs can be used to model relationships such as:
    - Friendships in a social network
    - Airline routes between cities
    - Connections in a computer network
- A graph can be represented as:
    - A diagram (dots and lines)
    - A set of ordered pairs (edges as relations)
- Some types of graphs include:
    - **Undirected graphs** (edges have no direction)
    - **Directed graphs (digraphs)** (edges have direction)
    - **Weighted graphs** (edges have weights, representing costs or distances)