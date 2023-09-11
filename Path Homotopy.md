# Definition
## Path Homotopic
Two [[Path|paths]] $f$ and $f'$, mapping the interval $I = [0, 1]$ into $X$, are said to be _path homotopic_ if they have the same initial point $x_0$ and the same finial point $x_1,$ and if there is a [[Homotopy#Homotopy|homotopy]] $F : I \times I \to X$ such that $$
	\begin{align}
		F(s, 0) &= f(s) & \text{and} && F(s, 1) &= f'(s),\\
		F(0, t) &= x_0 & \text{and} && F(1, t) &= x_1,
	\end{align}$$for each $s \in I$ and each $t \in I.$
### Remarks
- If $f$ is [[Path Homotopy#Path Homotopic|path homotopic]] to $f'$, we will sometimes write $f \simeq_p f'.$
## Path Homotopy
If $f$ and $f'$ are [[Path Homotopy#Path Homotopic|path homotopic]], then the [[Homotopy#Homotopy from maps f to g|homotopy between]] $f$ and $f'$ is called the _path homotopy_.
### Remarks
- Essentially, a [[Path Homotopy#Path Homotopy|path homotopy]] is [[Homotopy#Homotopy|homotopy]] with the endpoints of the path fixed.
# Examples
- An illustration of a [[Path Homotopy#Path Homotopic|path homotopy]]. ![[Pasted image 20230911063944.png]]
- Let $f$ and $g$ be any two maps of a space $X$ into $\mathbb{R}^2.$ The map $$F(x, t) = (1 - t)f(x) + tg(x)$$ is a [[Homotopy#Homotopy|homotopy]] between them. It is called a [[Straight-line Homotopy|straight-line homotopy]]
# Theorems
## Theorem
The relations $\simeq$ and $\simeq_p$ are [[Equivalence Relation|equivalence relations]] \[[[Theorem-d87bc5057cf61aea4f54251207bd7e47955a566d497fe5915a88a756be810f7536df652162e8b03b3137898724c132746f19721496e0e90f08b67c9f2bdda5d4|Proof]]\]