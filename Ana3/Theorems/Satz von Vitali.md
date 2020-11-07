# Satz von Vitali #Ana3
Es gibt keine Abbildung $\mu:\mathscr{P}(\mathbb{R})^n\to [0,\infty]$ mit folgenden Eigenschaften
1. Monotonie: $A\subseteq B\subseteq \mathbb{R}^n\implies \mu(A)\leq \mu(B)$.
2. Euklidische Invarianz: $A\subseteq \mathbb{R}^n;T:\mathbb{R^n}\to\mathbb{R^n}$ [affine Isometrie](Affine%20Isometrie.md), dann $\mu(A)=\mu(TA)$. 
3. Normiert:  $\forall_{l\geq 0}:\mu([0,l]^n)=l^n$.
4. $\sigma$- Additivität: Falls $(A_j)_{j\in\mathbb{N}}$ paarweise  disjukte Teilmengen vom $\mathbb{R}^n$ sind, dann $\mu(\cup_{j=0}^\infty A_j)=\sum_{j=0}^\infty \mu(A_j)$.

Es gibt ebenfalls keine solche Abbildung, falls man 2. durch
- $\forall_{x\in\mathbb{R}^n}\forall_{A\subseteq\mathbb{R}^n}$ gilt $\mu(A)=\mu(A+x)$