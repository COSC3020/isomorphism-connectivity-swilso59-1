[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Proof:
- if there are 2 graphs:
- $G_1$ with the vertices A, B and C, only A and B are connected.
- $G_2$ with vertices 1, 2, and 3, only 1 and 2 are connected.
- if we map A to 1, B to 2, and C to 3. This maintains the corresponding edges.
- This mapping shows bijection since there exists both a one-to-one and onto function.
- We can now see that even though the graphs are not commpletely connected there exists a bijective function and
  preserves the edges the are isomorphic.  
  

// isomorphism-connectivity-IshitaPatel18
// isomorphism-connectivity-Dhruv8806
// isomorphism-connectivity-rzafft1
