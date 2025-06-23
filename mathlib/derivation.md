---
version: "0.1"
status: done
---

#principal 
Let $K$ be a ring or a field, $A$ a $K$-algebra, and $M$ an $A$-bimodule.
A $K$-linear map
$$D: A \rightarrow M$$
is called a $K$-derivation if for all $a, b \in A$, the following Leibniz rule holds:
$$D(a b)=a \cdot D(b)+D(a) \cdot b$$
where the multiplications denote the left and right $A$-module actions of $A$ on $M$, respectively.
# property
source: [wiki](https://en.wikipedia.org/wiki/Derivation_(differential_algebra)#Properties)

If $A$ is a $K$-algebra, for $K$ a ring, and $D: A \rightarrow A$ is a $K$-derivation:

1. If $A$ has a unit $1$
$$D(k)=0 \quad \text{for}\ k \in K \tag{2.1}$$
2. 
$$
D\left(x_1 x_2 \cdots x_n\right)=\sum_i x_1 \cdots x_{i-1} D\left(x_i\right) x_{i+1} \cdots x_n \tag{2.2}
$$
> [!NOTE]
> If $A$ is commutative, $D\left(x^n\right)=n x^{n-1} D(x)$ is a corollary of 2.2

3. $\mathrm{Der}_{K}(A,M)$ is a module over $K$
4. $\mathrm{Der}_{K}(A)$ is a Lie algebra with Lie bracket defined by $\left[D_1,D_2\right] = D_1 \circ D_2 - D_2 \circ D_1$
5. There is an $A$-module $\Omega_{A / K}$ (called the Kähler differentials) with a $K$-derivation $d: A \rightarrow \Omega_{A / K}$ through which any derivation $D: A \rightarrow M$ factors. That is, for any derivation $D$ there is a $A$-module map $\varphi$ with
$$
D: A \xrightarrow{d} \Omega_{A / K} \xrightarrow{\varphi} M
$$

> [!Corollary]
> $$\mathrm{Der}_K(A, M) \simeq \mathrm{Hom}_A\left(\Omega_{A / K}, M\right)$$

6. If $k \subset K$ is a subring, then $A$ inherits a $k$-algebra structure, so there is an inclusion $\operatorname{Der}_K(A, M) \subset \operatorname{Der}_k(A, M)$, since any $K$-derivation is a fortiori a $K$-derivation.
