# konvexe Dinge #DataInf
Sei $X=\{x_1,\dots,x_n\}\in\mathbb{R}^m$ eine endliche Menge von [Vektoren](Datenzentrierte%20Informatik/Definitionen/Vektoren.md).
Ein Vektor $x\in\mathbb{R}^m$ ist eine ==konvexe Kombination== der Vektoren in X, wenn er eine lineare Kombination
$$x=\sum_{j=1}^n w_jx_j$$ ist und die Koeffizienten $w_j\in\mathbb{R}^m$ folgende Bedingungen erfüllen:
$$w_j\geq 0$$ $$\sum_{j=1}^nw_j=1$$
Wir können dies kondensieren :
$$X=\begin{bmatrix}
		|&|&&|\\
		x_1&x_2&\dots&x_n\\
		|&|&&|
	   \end{bmatrix},w=
	   \begin{bmatrix}w_1\\\vdots\\w_n\end{bmatrix},
	   1=\begin{bmatrix}1\\\vdots\\1\end{bmatrix},
	   0=\begin{bmatrix}0\\\vdots\\0\end{bmatrix}$$
und schreiben dann
$$x=Xw$$
$$w\succeq 0$$
$$1^\top w=1$$
## Konvexe Mengen
Eine Menge $S\subseteq\mathbb{R}^m$ ist eine ==konvexe Menge==, wenn
jeder Punkt auf dem Liniensegment zwischen irgend
zwei Punkten in S ebenfalls in S liegt:
$$\forall_{x_1,x_2\in S}\land \forall_{w\in[0,1]}:wx_1+(1-w)x_2\in S.$$
## Beispiele Konvexer Mengen
- $\emptyset,\mathbb{R}^m$
- Unterräume, [Halbräume](Datenzentrierte%20Informatik/Definitionen/Halbraum.md)
- der endliche Schnitt von konvexen Mengen $(S_i)_{i=1}^n$
## Extrempunkte
Ein ==Extrempunkt== einer konvexen Menge S ist ein Punkt $x\in S$, der nicht als konvexe Kombination anderen Punkte in S erzeugt werden kann.
## Konvexe Hülle
Die ==konvexe Hülle== $C(S)$ von $S\subseteq\mathbb{R}^m$ ist die Menge aller konvexer Kombinationen von Punkten von S:
$$C(S)=\left\{\sum_{x_j\in R}w_jx_j|R\subseteq S, |R|<\infty,w\succeq0,1^\top w=1\right\}$$.
Der ==Satz von Krein Milman== zeigt, dass jede kompakte konvexe Menge die konvexe Hülle ihrer Extrempunkte ist. 
## Siehe auch
- #DataInfVL6 