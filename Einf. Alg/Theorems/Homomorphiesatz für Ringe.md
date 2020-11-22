# Homomorphiesatz für Ringe #EinfAlg 
Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md), I ein [Ideal](Einf.%20Alg/Definition/Ideal.md) von R und $f:R\to S$ ein [Ringhomomorphismus](Einf.%20Alg/Definition/Ringhomomorphismus.md) mit $I\subseteq$[$\ker(f)$](Einf.%20Alg/Definition/Kern.md). Dann gelten:
- Es existiert genau eine Abbildung $\phi:$[$R/I$](Einf.%20Alg/Definition/Faktorringe.md)$\to S$ mit $f=\phi \pi_{M,K}$, und diese ist ein Ringhomomorphismus.
- Genau dann ist $\phi$ injektiv, wenn $\ker(f)=I$ gilt.
- Genau dann ist $\phi$ surjektiv, wenn $f$ surjektiv ist.
- Genau dann ist $\phi$ ein Isomorphismus, wenn $f$ surjektiv und $I=\ker(f)$ ist.
## Anmerkungen
- Der erste Punkt kann auch so formuliert werden: $\pi_{M,K}:M\to M/k$ hat die [universellen Eigenschaft](universellen%20Eigenschaft) für $R-$Modulmorphismen $f:M\to N$ mit $f|_K=0$.
- Wie bei der [Lokalisierung](Einf.%20Alg/Theorems/Lokalisierung.md) oder dem [Quotientenkörper](Einf.%20Alg/Definition/Konsturktion%20des%20Quotientenk%C3%B6rpers.md) charakterisiert diese universelle Eigenschaft $M/K$ [eindeutig bis auf eindeutigen Homomorphismus](Einf.%20Alg/Theorems/Eindeutige%20Bestimmtheit%20durch%20die%20unverselle%20Eigenschaft.md).
## Siehe auch
- #EinfAlgVL7 