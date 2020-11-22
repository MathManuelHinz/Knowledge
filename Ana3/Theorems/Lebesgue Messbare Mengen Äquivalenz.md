# Lebesgue Messbare Mengen Äquivalenz #Ana3 
Folgende Aussagen sind äquivalent:
- $A\in$ [$\mathcal{M}_n$](Ana3/Definitions/Lebesgue-Ma%C3%9F.md).
- Für alle $\epsilon >0$ gibt es eine offene Menge $=O_\epsilon\subseteq\mathbb{R}^n$ mit $A\subseteq O_\epsilon$ und $\mathcal{L}^{n*}(O_\epsilon\setminus A)\leq \epsilon.$
- Für alle $\epsilon >0$ gibt es eine abgeschlossene Menge $C_\epsilon\subseteq\mathbb{R}^n$ mit $C_\epsilon\subseteq A$ und $\mathcal{L}^{n*}(A\setminus C_\epsilon)\leq \epsilon.$
Insbesondere gilt auch:
$$\mathcal{L}^n(A)=\sup\{\mathcal{L}^n(K):\text{K kompakt, }K\subseteq A\}\text{       (innere Regularität)}$$
$$=\inf\{\mathcal{L}^n(O):\text{K offen, }A\subseteq O\}\text{       (äußere Regularität)}$$
## Siehe auch
- #Ana3VL5
- #Ana3VL6