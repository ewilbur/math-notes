# Definition
## Differentiable at a Point
A function $f : \mathbb{R}^n \to \mathbb{R}^m$ is *differentiable at $a \in \mathbb{R}^n$* if there is a [[Linear Map|linear transformation]] $\lambda : \mathbb{R}^n \to \mathbb{R}^m$ such that 
$$
	\lim_{h \to 0} \frac{|f(a + h) - f(a) - \lambda(h)|}{h} = 0.
$$
### Remark
- Note that $h \in \mathbb{R}^n$ and $f(a + h) - f(a) - \lambda(h) \in \mathbb{R}^m,$ so the norm signs are necessary.
- The [[Linear Map|linear transformation]] $\lambda$ is denoted $Df(a)$ and called the [[Derivative|derivative]] of $f$ at $a.$ ^0ff243

## Differentiable on a Subset
A function $f : \mathbb{R}^n \to \mathbb{R}^m$ which is [[Differentiable#Differentiable at a Point|differentiable]] at every point $p \in A \subseteq \mathbb{R}^n$ is called *differentiable on $A$*.
# Theorems
## Theorem-e405a769
If $f : \mathbb{R}^n \to \mathbb{R}^m$ is [[Differentiable#Differentiable at a Point|differentiable]] at $a \in \mathbb{R}^n,$ then there is a unique [[Linear Map|linear transformation]] $\lambda : \mathbb{R}^n \to \mathbb{R}^m$ such that 
$$
	\lim_{h \to 0} \frac{|f(a + h) - f(a) - \lambda(h)|}{h} = 0.
$$
\[[[Theorem-e405a76914007b8b874697e64245a1292d6ec4ccb2015f18d0475de79ece8bddabf65e90525a87762bd4fede624c61b91ada90355911b37bb4d4146ccd3c808e|Proof]]\]
### Remark
- With this theorem, it makes sense to think of *the* [[Derivative#Derivative|derivative]] at a point. In other words, the [[Derivative#Derivative|derivative]] is unique.
## [[Theorem-42f27a4278c240efd4780529615aba34afaa4c13b8f03fe12f6ac5140a7072ab5a354952f23fec5342fd524ef4cf5b3af63cbabda8c6fe97bb36d2f8db85951e|The Chain Rule]]
If $f : \mathbb{R}^n \to \mathbb{R}^m$ is [[Differentiable#Differentiable at a Point|differentiable]] at $a,$ and $g : \mathbb{R}^m \to \mathbb{R}^p$ is [[Differentiable#Differentiable at a Point|differentiable]] at $f(a),$ then the composition $g \circ f$ is [[Differentiable#Differentiable at a Point|differentiable]] at $a,$ and
$$
	(g \circ f)'(a) = g'(f(a))\cdot f'(a).
$$

^8a9aec

\[[[Theorem-42f27a4278c240efd4780529615aba34afaa4c13b8f03fe12f6ac5140a7072ab5a354952f23fec5342fd524ef4cf5b3af63cbabda8c6fe97bb36d2f8db85951e|Proof]]\]
### Remark
- The [[Differentiable#^8a9aec|equation]] can be equivalently written as $$D(g \circ f)(a) = Dg(f(a)) \circ Df(a).$$