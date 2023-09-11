# Definition
## Tangent Vector to $M$ at $m$
Let $M$ be an [[Manifold#Abstract Manifold|abstract manifold]] and $m \in M.$ A _tangent vector_ to $M$ at $m$ is an [[Equivalence Relation#Equivalence Class|equivalence class]] of curves $c : I \to M,$ where $I$ is an interval containing 0 and such that $c(0) = m,$ for the [[Equivalence Relation#Equivalence Relation|equivalence relation]] $\sim$ defined by $$c \sim \gamma \iff \text{in a chart } (U, \phi) \text{ around } m, \text{we have } (\phi \circ \gamma)'(0) = (\phi \circ c)'(0).$$
### Remark
- This notion does not depend on the chart since $$(\phi \circ c)'(0) = (\psi \circ \phi^{-1})'(\phi(m)) \cdot (\phi \circ c)'(0).$$ \[[[Theorem-8c7a451baa17971322aa7882717e6d6d29011c7031f062077968f0bd3f01e710159bae0b0db575d8e802d3f190bd9a858fde32a510df344c7dcd22c5928fd402|Proof]]\]
- A [[Tangent Vector#Tangent Vector to $M$ at $m$|tangent vector]] to $M$ at $m$ is then a class of triples $(U, \phi, u)$ for the [[Equivalence Relation#Equivalence Relation|equivalence relation]] $\sim.$ ^00798b

## Tangent Vector
Let $M$ be a [[Manifold|manifold]], $m \in M, (U, \phi)$ and $(V, \psi)$ be two [[Chart|charts]] for $M$ around $m$. Let $u$ and $v$ be two [[Vector|vectors]] in $\mathbb{R}^n$ (you have to consider them as tangent vectors to $\mathbb{R}^n$ at $\phi(m)$ and $\psi(m)$ respectively). We say that $$(U, \phi, u) \sim (V, \psi, v) \iff (\psi \circ \phi^{-1})'_{\phi(m)}\cdot u = v.$$ A *tangent vector* to $M$ at $m$ is then a [[Tangent Vector#^00798b|class of triples]]  $(U, \phi, u)$ for the [[Equivalence Relation#Equivalence Relation|equivalence relation]] $\sim.$

# Remark
- In [[Tangent Vector#Tangent Vector to $M$ at $m$|the first definition]], a vector $\xi \in T_mM$ is represented by a curve $c.$ In [[Tangent Vector#Tangent Vector|the second one]], this vector is represented in the [[Chart#Chart|chart]] $(U, \phi)$ by a [[Vector#Vector|vector]] $u \in \mathbb{R}^n.$ We get the equivalence of the two definitions by considering $u = (\phi \circ c)'(0).$ \[[[Theorem-99dc451ccee854007357acb8126ad34a88cd7253857df1f794634ea87dcfdc381ac9789b99bb0f5239b4a60e799ff2b02ff2c9575eb1b26e842c2d5a36cbfcc8|Proof]]\]
# Theorems
## Theorem
The set of [[Tangent Vector#Tangent Vector to $M$ at $m$|tangent vectors]] to $M$ at $m$ is an $n$-dimensional [[Vector Space|linear subspace]] of $\mathbb{R}^{n + k},$ that we denote by $T_mM.$   