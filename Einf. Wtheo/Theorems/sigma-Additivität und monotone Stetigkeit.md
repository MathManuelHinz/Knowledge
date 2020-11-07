# $\sigma$-Additivität und monotone Stetigkeit #EinfWth
Sei $\mathscr{F}$ eine [$\sigma$-Algebra](sigma-Algebra.md) und $\mu:\mathscr{F}\to\mathbb{R}_{\geq 0}$ additiv, d.h. $\mu(A\cup B)=\mu(A)+\mu(B)$, wenn $A\cap B=\emptyset$. Dann
- $\mu$ ist $\sigma$-additiv genau dann wenn $$A_1\subseteq A_2\subseteq \dots \implies \mu(\cup_{n\geq 1}A_n)=\lim\limits_{n\to\infty}\mu(A_n)\text{ (stetig von unten)}$$
- Gilt $\mu(\Omega)<\infty$, dann ist dies auch äquivalent zu: $$A_1\supseteq A_2\supseteq \dots \implies \mu(\cap_{n\geq 1}A_n)=\lim\limits_{n\to\infty}\mu(A_n) \text{ (stetig von oben)}$$
## Siehe auch