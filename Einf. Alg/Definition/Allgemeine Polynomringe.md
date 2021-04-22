# Allgemeine Polynomringe #EinfAlg 
Für eine Menge X von Variablen sei $M_X$ die Menge aller Funktionen $\alpha:X\to\mathbb{N}$, s.d. nur endlich viele $x\in X$ mit $\alpha(x)\neq 0$ existieren. Für $\alpha,\beta\in M_X$ definieren wir $\alpha+\beta\in M_X$ durch $(\alpha+\beta)(x)=\alpha(x)+\beta(x)$. Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md). Wenn $\alpha\in M_X$ und $r=(r_x)_{x\in X}$ eine Funktion $X\to R$ ist, schreiben wir $$r^\alpha=\prod_{x\in X}r^{\alpha(x)}_x.$$
Sei $R[x|x\in X]$ die Menge aller Familien $P=(p_\alpha)_{\alpha\in M_X}$, so dass nur endlich viele $\alpha\in M_X$ mit $p_\alpha\neq 0$ existieren, versehen mit der Ringstruktur
$$(P+Q)_\alpha=p_\alpha+q_\alpha$$
$$(PQ)_\alpha=\sum_{\alpha=\beta+\gamma\in M_X}p_\beta q_\gamma.$$
Für $r=(r_x)_{x\in X}$ wie zuvor sei $P(r)=\sum_{\alpha\in M_X}p_\alpha r^\alpha$. Für $X=\{X_1,\dots,X_n\}$ schreiben wir $R[X_1,\dots,R_n]$ statt $R[x|x\in X]$.
## Bemerkung
- Für $X=\{T\}$ kann $M_X$ durch $\alpha\to\alpha(T)$ mit der Menge der natürlichen Zahlen identifiziert werden, und $R[x|x\in X]\cong R[T]$.
- Für jede Familie $r=(r_x)_{x\in X}$ ist durch $R[x|x\in X]\to X, P\mapsto P(r)$, ein [Ringhomomorphismus](Einf.%20Alg/Definition/Ringhomomorphismus.md) definiert.
- Wenn $X=Y\cup Z$ (disjunkte Vereinigung), so haben wir zueinander inverse Isomorphismen $R[x|x\in X]\cong(R[y|y\in Y])[z|z\in Z]$, welche einem $P\in R[x\in X]$ das durch $(Q_\gamma)_\beta=P_{\beta\#\gamma}(\beta \in M_Y,\gamma \in M_Z)$ definierte $Q\in (R[y|y\in Y])[z|z\in Z]$ und einem solchen Q das durch $P_\alpha=(Q_{\alpha|Z})_{\alpha|Y}$ definiert $P\in R[x|x\in X]$ zuordnen. Insbesondere
- $R[X_1,\dotsm,X_m,Y_1,\dots,Y_n]\cong (R[X_1,\dotsm,X_m])[Y_1,\dots,Y_n]$.
## Siehe auch
- #EinfAlgVL13 