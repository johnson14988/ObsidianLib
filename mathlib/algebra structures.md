#glossary #principal 
# [[group]]
$\langle G, \cdot,^{-1}, 1\rangle$ satisfies
$$
\begin{align}
&\text {G1: } x \cdot(y \cdot z) \approx(x \cdot y) \cdot z \\
&\text {G2: } x \cdot 1 \approx 1 \cdot x \approx x \\
&\text {G3: } x \cdot x^{-1} \approx x^{-1} \cdot x \approx 1 \\
&\text {G4: } x \cdot y \approx y \cdot x \quad \text{(for Abelian groups)}
\end{align}
$$
# [[semigroup]]
$\langle G,\cdot \rangle$ satisfies G1
# [[monoid]]
$\langle M,\cdot,1 \rangle$ satisfies G1 and G2
# [[quasigroup]]
$\langle Q, /, \cdot, \backslash\rangle$ satisfies
$$
\begin{align}
&\text{Q1: } x \backslash(x \cdot y) \approx y ;(x \cdot y) / y \approx x \\
&\text{Q2: } x \cdot(x \backslash y) \approx y ;(x / y) \cdot y \approx x
\end{align}
$$
# [[loop]]
$\langle Q, /, \cdot, \backslash,1\rangle$ satisfies Q1, Q2, G2
# [[ring]]
$\langle R,+,\cdot,-,0\rangle$ satisfies
$$
\begin{align}
\text{R1: } &\langle R,+,-, 0\rangle\ \text{is an Abelian group} \\
\text{R2: } &\langle R, \cdot\rangle\ \text{is a semigroup} \\
\text{R3: } &x \cdot(y+z) \approx(x \cdot y)+(x \cdot z) \\
            &(x+y) \cdot z \approx(x \cdot z)+(y \cdot z)
\end{align}
$$
# [[module over a ring]] $\mathrm{R}$
$\left\langle M,+,-, 0,\left(f_r\right)_{r \in R}\right\rangle$ satisfies
$$
\begin{align}
&\text{M1: } \langle M,+,-, 0\rangle\ \text{is an Abelian group} \\
&\text{M2: } f_r(x+y) \approx f_r(x)+f_r(y),\ \text{for}\ r \in R \\
&\text{M3: } f_{r+s}(x) \approx f_r(x)+f_s(x),\ \text{for}\ r, s \in R \\
&\text{M4: } f_r\left(f_s(x)\right) \approx f_{r s}(x)\ \text{for}\ r, s \in R \\
&\text{M5: } f_1(x) \approx x \quad \text{for unitary R-module}
\end{align}
$$
# [[algebra over a ring]] $\mathrm{R}$ with identity
$\left\langle A,+, \cdot,-, 0,\left(f_r\right)_{r \in R}\right\rangle$ satisfies
$$
\begin{align}
&\text{A1: } \left\langle A,+,-, 0,\left(f_r\right)_{r \in R}\right\rangle\ \text{is a unitary R-module} \\
&\text{A2: } \langle A,+, \cdot,-, 0\rangle\ \text{is a ring} \\
&\text{A3: } f_r(x \cdot y) \approx\left(f_r(x)\right) \cdot y \approx x \cdot f_r(y)\ \text{for}\ r \in R
\end{align}
$$

# [[semilattice]]
a semigroup $\langle S,\cdot \rangle$ satisfies
$$
\begin{align}
&\text{S1: } x \cdot x \approx x \\
&\text{G4}
\end{align}
$$
# [[lattice]]
$\langle L,\vee,\wedge \rangle$ satisfies
$$
\begin{align}
\text{L1: } &x \vee y \approx y \vee x\\
            &x \wedge y \approx y \wedge x \\
\text{L2: } &x \vee (y \vee z) \approx (x \vee y) \vee z \\
            &x \wedge (y \wedge z) \approx (x \wedge y) \wedge z \\
\text{L3: } &x \vee x \approx x \\
            &x \wedge x \approx x \\
\text{L4: } &x \approx x \vee (x \wedge y) \\
            &x \approx x \wedge (x \vee y) \\
\end{align}
$$
# [[bounded lattice]]
$\langle L,\vee,\wedge,0,1 \rangle$ satisfies
$$
\begin{align}
\text{BL1: } &\langle L, \vee, \wedge\rangle\ \text{is a lattice} \\
\text{BL2: } &x \wedge 0 \approx 0 \\
             &x \vee 1 \approx 1
\end{align}
$$
# [[boolean algebra]]
$\langle B,\vee,\wedge,^\prime,0,1 \rangle$ satisfies
$$
\begin{align}
\text{B1: } &\langle B, \vee, \wedge\rangle\ \text{is a distributive lattice} \\
\text{B2: } &x \wedge 0 \approx 0 \\
            &x \vee 1 \approx 1 \\
\text{B3: } &x \wedge x^{\prime} \approx 0 \\
            &x \vee x^{\prime} \approx 1
\end{align}
$$
# [[Heyting algebra]]
$\langle H,\vee,\wedge,\rightarrow,0,1 \rangle$ satisfies
$$
\begin{align}
\text{H1: } &\langle H, \vee, \wedge\rangle\ \text{is a distributive lattice} \\
\text{H2: } &x \wedge 0 \approx 0 \\
            &x \vee 1 \approx 1 \\
\text{H3: } &x \rightarrow x \approx 1 \\
\text{H4: } &(x \rightarrow y) \wedge y \approx y \\
            &x \wedge(x \rightarrow y) \approx x \wedge y \\
\text{H5: } &x \rightarrow(y \wedge z) \approx(x \rightarrow y) \wedge(x \rightarrow z) \\
            &(x \vee y) \rightarrow z \approx(x \rightarrow z) \wedge(y \rightarrow z)
\end{align}
$$
# $n$-valued [[Post algebra]]
satisfies every identity satisfied by the algebra $\mathbf{P}_n=\left\langle\{0,1, \ldots, n-1\}, \vee, \wedge,{ }^{\prime}, 0,1\right\rangle$ where $\langle\{0,1, \ldots, n-1\}, \vee, \wedge, 0,1\rangle$ is a bounded chain with $0<n-1<n-2<\cdots<2<1$, and $1^{\prime}=2,2^{\prime}=3, \ldots,(n-2)^{\prime}=$ $n-1,(n-1)^{\prime}=0$, and $0^{\prime}=1$
# [[cylindric algebra]] of dimension $n$
$\left\langle A, \vee, \wedge,^{\prime}, c_0, \ldots, c_{n-1}, 0,1, d_{00}, d_{01}, \ldots, d_{n-1, n-1}\right\rangle$ ($n\in\omega$) satisties
for $0 \leq i,j,k < n$
$$
\begin{align}
\text{C1: } &\left\langle A,\vee,\wedge,{ }^{\prime},0,1\right\rangle\ \text{is a Boolean algebra} \\
\text{C2: } &c_i 0 \approx 0 \\
\text{C3: } &x \leq c_i x \\
\text{C4: } &c_i\left(x \wedge c_i y\right) \approx\left(c_i x\right) \wedge\left(c_i y\right) \\
\text{C5: } &c_i c_j x \approx c_j c_i x \\
\text{C6: } &d_{i i} \approx 1 \\
\text{C7: } &d_{i k} \approx c_j\left(d_{i j} \wedge d_{j k}\right)\ \text{if}\ i \neq j \neq k \\
\text{C8: } &c_i\left(d_{i j} \wedge x\right) \wedge c_i\left(d_{i j} \wedge x^{\prime}\right) \approx 0\ \text{if}\ i \neq j
\end{align}
$$
# [[ortholattice]]
$\langle L,\vee,\wedge,{}^\prime,0,1\rangle$ satisfies
$$
\begin{align}
\text{O1: } &\langle L, \vee, \wedge, 0,1\rangle\ \text{ is a bounded lattice } \\
\text{O2: } &x \wedge x^{\prime} \approx 0 \\
            &x \vee x^{\prime} \approx 1 \\
\text{O3: } & (x \wedge y)^{\prime} \approx x^{\prime} \vee y^{\prime} \\
            &(x \vee y)^{\prime} \approx x^{\prime} \wedge y^{\prime} \\
\text{O4: } &\left(x^{\prime}\right)^{\prime} \approx x \\
\text{O5: } &x \leq y \rightarrow x \vee\left(x^{\prime} \wedge y\right) \approx y\quad \text{(for orthomodular lattices)}
\end{align}
	$$