# Homomorphiesatz für Moduln #EinfAlg 
Sei K ein [Untermoduln](Einf.%20Alg/Definition/Untermoduln.md) des r[Modules](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) M und $f:M\to N$ ein [R-Modulmorhpismus](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md) mit $K\subseteq$[$\ker(f)$](Einf.%20Alg/Definition/Kern.md). Dann gelten:
- Es existiert genau eine Abbildung $\phi:$[$M/K$](Einf.%20Alg/Definition/Faktormoduln.md)$\to N$ mit $f=\phi \pi_{M,K}$, und diese ist ein Morphismus von R-Moduln.
- Genau dann ist $\phi$ injektiv, wenn $\ker(f)=K$ gilt.
- Genau dann ist $\phi$ surjektiv, wenn $f$ surjektiv ist.
- Genau dann ist $\phi$ ein Isomorphismus, wenn $f$ surjektiv und $K=\ker(f)$ ist.
## Anmerkungen
- Der erste Punkt kann auch so formuliert werden: $\pi_{M,K}:M\to M/k$ hat die [universellen Eigenschaft](universellen%20Eigenschaft) für $R-$Modulmorphismen $f:M\to N$ mit $f|_K=0$.
- Wie bei der [Lokalisierung](Einf.%20Alg/Theorems/Lokalisierung.md) oder dem [Quotientenkörper](Einf.%20Alg/Definition/Konsturktion%20des%20Quotientenk%C3%B6rpers.md) charakterisiert diese universelle Eigenschaft $M/K$ [eindeutig bis auf eindeutigen Homomorphismus](Einf.%20Alg/Theorems/Eindeutige%20Bestimmtheit%20durch%20die%20unverselle%20Eigenschaft.md).
## Siehe auch
![](Res/Pasted%20image%2020201121175304.png)
- #EinfAlgVL7 