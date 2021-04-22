# Hauptsatz der Galois-Theorie #EinfAlg 
Sei $M/K$ eine [endliche](Einf.%20Alg/Definition/Endliche%20K%C3%B6rpererweiterung.md) [Galois-Erweiterung](Einf.%20Alg/Definition/Galois-Erweiterung.md) und $G=\text{Gal}(M/K):=\text{Aut}(M/K)$ deren ==Galois-Gruppe.==
- Wenn $K\subseteq L \subseteq M$ ein Zwischenkörper ist, so ist $M/L$ eine  Galois-Erweiterung.
- Wir haben eine Bijektion zwischen allen Zwischenkörpern
$$\text{Menge der Zwischenkörper }L\cong\text{Untergruppen } H\subseteq G$$
Mit folgenden Abbildungen
$$L\mapsto \text{Gal(M/L)}$$
$$\text{Gal(M/L)}=H\mapsto M^H$$
- Unter dieser Bijektion gilt $[M:L]=\#H$ und $[L:K]=\#(G/H)$ (Zahl der Rechtsnebenklassen, welche übereinstimmt mit der Zahl der Linksnebenklassen), und es entsprechen die Normalteiler $H\subseteq G$ genau den Zwischenkörpern $K\subseteq L \subseteq M$, welche Galois-Erweiterungen von K sind. In diesem Fall gibt es genau einen Isomorphismus $\iota:G/H\to\text{Gal(L/K)}$ mit $\iota(\pi_{G,H}(\sigma))=\sigma_L$.
## Beispiel
#Todo
## Siehe auch
- #EinfAlgVL16 