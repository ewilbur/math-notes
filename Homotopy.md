# Definitions
## Homotopy
A _homotopy_ is a family of maps $f_t : X \to Y, t \in I$, such that the associated map $F: X \times I \to Y$ given by $F(x, t) = f_t(x)$ is [[Continuity|continuous]].
## Associated Map
Given a [[Homotopy#Homotopy|homotopy]] $f_t : X \to Y$, the map $F:X \times I \to Y$ given by $F(x, t)$ is called the _associated map_ of the [[Homotopy#Homotopy|homotopy]].
## Homotopic
If $f$ and $f'$ are [[Continuity#Continuous|continuous]] maps of the space $X$ into the space $Y$, we say that $f$ is _homotopic_ to $f'$ if there is a continuous map $F : X \times I \to Y$ such that
$$
	\begin{align}
		F(x, 0) = f(x) && \text{and} && F(x, 1) = f'(x)
	\end{align}
$$
for each $x$.
### Remarks
- If $f$ is [[Homotopy#Homotopic|homotopic]] $f'$, we write $f \simeq f'$.
- If $f \simeq f'$ and $f'$ is a constant map, then we say that $f$ is [[Nulllhomotopic#Nullhomotopic|nullhomotopic]].
## Homotopy from maps f to g
If $f \simeq g$, then $F : X \times I \to Y$ is _a homotopy from $f$ to $g$_ if $F$ is a [[Homotopy#Homotopy|homotopy]], $F(x,0) = f,$ and $F(x,1) = g.$
# Remarks
- In the above definitions, $X \times I$ is taken to have the [[Product Topology|product topology]].
# Examples
- [[Deformation Retraction]]
- [[Path Homotopy]]
# Theorems
- Let $f_t : X \to Y$ be a [[Homotopy#Homotopy|homotopy]] and let $\varphi : I \to I$ be [[Continuity|continuous]]. The family of maps $f_{\varphi(t)}$ is a [[Homotopy#Homotopy|homotopy]]. \[[[Theorem-e1caee05e6cb6cc3fd3abd8c002cfb2147b4b1762f75ee198d3eac11eb04af2de8f884cc68e6caf932f2dd1a6ad29f37290f4ab0aeb7fda2ca808c748044b28b|Proof]]\]
