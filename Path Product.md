# Definition
## Path Product
If $f$ is a [[Path#Path|path]] in $X$ from $x_0$ to $x_1,$ and if $g$ is a [[Path#Path|path]] in $X$ from $x_1$ to $x_2,$ we define the _product_ (i.e. _path product_) $f * g$ of $f$ and $g$ to be the [[Path#Path|path]] $h$ given by the equations
$$
	h(s) = \begin{cases}
		f(2s) & \text{for } s \in [0, \frac{1}{2}],\\
		g(2s - 1) & \text{for } s \in [\frac{1}{2}, 1].
	\end{cases}
$$
# Theorems
## Theorem-b7308b57
The [[Path Product#Path Product|path product]] is well-defined and continuous. \[[[Theorem-b7308b5734b324c5dcd2a8321f966a8d243d19d3378cbe4fc889d9ab92aa635891380d2e336daf4222ec4c8274db4c68e41bdb765b4fbc466a353d4f01c563b9|Proof]]\]
## Theorem-7b982dfa
The [[Path Product#Path Product|path product]] induces a well-defined operation on [[Path Homotopy#Path Homotopy|path-homotopy]] classes, defined by the equation $$[f]*[g] = [f*g].$$ \[[[Theorem-7b982dfaab31cc66ab2fe1f02454c30d97bcfb41c10a568ab28e1488e3518a54ee9125a36b7d5ea07db06b4ebb0dfc53f93927cf0d4546900ae5f204db631bf8|Proof]]\]
## Theorem-57ad2300
Let $f$ be a [[Path#Path|path]] in $X,$ and let $a_0,...,a_n$ be numbers such that $0 = a_0 < a_1 < ... < a_n = 1.$ Let $f_i : I \to X$ be the [[Path#Path|path]] that equals the [[Positive Linear Map|positive linear map]] of I onto $[a_{i-1},a_i]$ followed by $f.$ Then $$[f] = [f_1]*...*[f_n].$$ \[[[Theorem-57ad23007b679a38d0bfb26fca8cc814552add0a85498e71179b1ea2be6d0dc48b45a0d5030efcbcd01776ee981ac2310b65b34668951ec559d3642b6ac87c68|Proof]]\]
### Remark
From the view of [[Path Product#Theorem-57ad2300|the above theorem]], any [[Path#Path|path]] can be decomposed into a finite number of component paths that are glued together.

## Theorem-4d89ff8e
The [[Path Product#Path Product|path product]] $*$ has the following properties
1. **Associativity**: If $[f] * ([g]*[h])$ is defined, so is $([f] *[g])*[h]$ and $$[f] * ([g]*[h]) = ([f] *[g])*[h].$$
2. **Right and left identities**: Given $x \in X,$ let $e_x$ define the constant path $e_x : I \to X$ carrying all of $I$ to the point $x.$ If $f$ is a path in $X$ from $x_0$ to $x_1,$ then $$ \begin{align}[f] * [e_{x_1}] = [f] && \text{and} && [e_{x_0}]*[f]=[f]\end{align}.$$
3. **Inverse**: Given the path $f$ in $X$ from $x_0$ to $x_1,$ let $\bar{f}$ be the path defined by $\bar{f}(s) = f(1 - s).$ It is called the [[Reverse Path| reverse]] of $f.$ Then $$ \begin{align}[f] * [\bar{f}] = [e_{x_0}] && \text{and} && [\bar{f}] * [f] = [e_{x_1}]\end{align}.$$\[[[Theorem-4d89ff8ea52eb2437f2dc280e3bdac87c621de63abdec8cbf881f2c6b3c5dc929cea13c9c59da419449c380c609493e73f68087a0a6301d42ef6b993db3a847c|Proof]]\]
