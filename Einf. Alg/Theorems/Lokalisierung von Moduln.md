# Lokalisierung von Moduln #EinfAlg 
Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md), S eine multiplikative Teilmenge, M ein R-[Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) Dann gibt es einen $R_S$-Modul $M_S$ und einen [Morphismus](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md) $j:M\to M_S$ von R-Moduln mit der Universellen Eigenschaft für derartige Morphismen: Wenn T ein $R_S$-Modul und $t:M\to T$ ein Morphismus von R-Moduln ist, so existiert genau ein  Morphismus $\tau:M_S\to T$ von $R_S$ Moduln mit $t=\tau j$. Diese [universellen Eigenschaft](universellen%20Eigenschaft) charakterisiert $M_S$ eindeutig, bis auf eindeutigen Isomorphismus.
![](Res/Pasted%20image%2020201127204600.png)
## Folgerung 1
Sei R ein [Integritätsbereich](Einf.%20Alg/Definition/Integrit%C3%A4tsbereich.md) mit [Quotientenkörper](Einf.%20Alg/Definition/Konsturktion%20des%20Quotientenk%C3%B6rpers.md) K, und sei S = R \ {0}. Wenn M
ein R-Modul ist, so gibt es einen K-[Vektorraum](LA1/Definitions/Vektorraum.md) $M_S$ und einen Morphismus $j:M\to M_S$
von R-Moduln, der die universelle Eigenschaft für derartige Morphismen hat, durch
welche er eindeutig bis auf eindeutigen Isomorphismus bestimmt ist: Wenn T ein K-Vektorraum
und $t:M_S\to T$ ein Morphismus von R-Moduln ist, so existiert genau eine
K-lineare Abbildung $\tau:M_S\to T$ mit $t=\tau j$.
## Folgerung 2
Wenn M endlich erzeugt als R-Modul ist, so ist $M_S$ endlich erzeugt als $R_S$-Modul (d.h. endlich [dimensional](LA1/Definitions/Dimension.md) als $R_S$-Vektorraum, falls $R$ ein Integritätsbereich und $S=R\setminus\{0\}$). Wenn M durch k seiner Elemente endlich erzeugt werden kann, so kann $M_S$ durch $\leq k$ seiner Elemente erzeugt werden. Wenn $X\subseteq M$ eine Erzeugendenmenge von M als $R$-Modul ist, so ist $\{[x,1]|x\in X\}$ eine Erzeugendenmenge von $M_S$ als $R_S$-Modul.
## Siehe auch
- [Lokalisierung](Einf.%20Alg/Theorems/Lokalisierung.md)
- #EinfAlgVL8 