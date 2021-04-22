# Endliche Körpererweiterung #EinfAlg 
Sei $L$ ein [Körper](LA1/Definitions/K%C3%B6rper.md) mit einem Unter[Ring](Einf.%20Alg/Definition/Ring.md) $K\subseteq L$, welcher selber ein Körper ist. In diesem Fall sprechen wir von einer ==Körpererweiterung== $L/K$. Durch seie additive [Gruppenstruktur](LA1/Definitions/Gruppe.md) und die Einschränkung auf $K\times L$ der Ringoperation der Multiplikation von L wird L zu einem K-Vektorraum.
## endliche Körpererweiterung
Die Körpererweiterung L=K ist ==endlich==, falls L endlichdimensional als K-Vektorraum
ist. In diesem Fall sagt man auch, dass ==L endlich über K== ist, und defininiert den ==Grad==
$[L : K]$ der Körpererweiterung als $dim_K L$, die Dimension des K-Vektorraumes L.
Unter einer ==Basis der Körpererweiterung== L=K versteht man eine Basis von L als K-
Vektorraum.
## Beispiele
- Die Körpererweiterung $\mathbb{C}/\mathbb{R}$ ist endlich mit Basis $(1,i)$, also $[\mathbb{C}:\mathbb{R}]=2$.
- Die Erweiterung $K/K$ ist endlich mit Basis $(1)$, also $[K:K]=1$. Jedes $x\in K$ erfüllt die algebraische Gleichung $P(x)=0$ mit $P[T]=T-x\in K[T]$. Also ist $K/K$ eine algebraische Körpererweiterung.
- Wenn $K\subseteq L\subseteq M$ ein ==Turm von Körpererweiterungen== und $M/K$ endlich (bzw. algebraisch), so ist auch $L/K$ endlich (bzw. algebraisch).
- Wenn $K=L_0\subseteq L_1\subseteq L_2\subseteq\dots$ eine Kette von algebraischen Körpererweiterungen von K ist, so ist auch $L=\subseteq_{i=0}^\infty L_i$ eine algebraische Körpererweiterung von K.
## Siehe auch
- #EinfAlgVL15