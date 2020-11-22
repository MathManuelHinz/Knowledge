# bedingte Wahrscheinlichkeit #EinfWth
Sei $(\Omega,\mathscr{F},\mathbb{P})$ ein [Wahrscheinlichkeitsraum](Einf.%20Wtheo/Definitions/Wahrscheinlichkeitsma%C3%9Fe.md), $A,B\in\mathscr{F}$ zwei Ereignisse. Für $B$ s.d. $\mathbb{P}(B)>0$, definieren wir 
$$\mathbb{P}(A|B)=\mathbb{P}_B(A):=\frac{\mathbb{P}(A\cap B)}{\mathbb{P}(B)},$$
die ==bedingte Wahrscheinlichkeit von A gegeben B==.
------------------------------------
Sei $B\in\mathscr{F}$ mit $\mathbb{P}(B)>0$. Dann
- Die bedingte Wahrscheinlichkeit $\mathbb{P}_B(\cdot)$ definiert ein Wahrscheinlichkeitsmaß auf $(B,\mathscr{F}_B)$, wobei
$$\mathscr{F}_B=\mathscr{F}\cap B:=\{A\cap B|A\in\mathscr{F}\}\subseteq \mathscr{F}.$$
- Sei $(B_n)_{n\in\mathbb{N}}$ eine Folge von paarweise disjunkten Mengen in $\mathscr{F}$, s.d.
	- $\cup_{n\in\mathbb{N}}B_n=\Omega$
	- $\mathbb{P}(B_n)>0$ für alle $n\in\mathbb{N}$
Dann, $\forall_{A\in\mathscr{F}}$:
$$\mathbb{P}(A=\sum_{n\in\mathbb{N}}\mathbb{P}(A|B_n)\mathbb{P}(B_n).$$
## Siehe auch
- #EinfWthVL7 