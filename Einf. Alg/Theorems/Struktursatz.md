# Struktursatz #EinfAlg 
Sei M ein endlich erzeugter [Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) über dem [Hauptidealbereich](Einf.%20Alg/Definition/Hauptidealbereiche.md) R. Dann gibt es natürliche Zahlen k und l sowie Folgen $(p_i)_{i=1}^l$ paarweise [multiplikativ inäquivalenter](Einf.%20Alg/Definition/multiplikativ%20%C3%A4quivalent.md) [Primelemente](Einf.%20Alg/Definition/Primelement.md) von R und und $(m_i)_{i=1}^l$ positiver ganzer Zahlen sowie eine Doppelfolge $(n_{i,j})_{i=1,j=1}^{l,m_i}$ positiver ganzer Zahlen mit $n_{i,1}\geq n_{i,2}\geq\dots\geq n_{i,m_i}$ s.d. ein Iso[Morphismus von R-Moduln](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md)
$$M\cong R^k\oplus\bigoplus_{i=1}^l\bigoplus_{j=1}^{m_i}R/p_i^{n_{i,j}}R$$
existiert. Diese zerlegung ist eindeutig bis auf Permutation der Summanden in der Summe über i und multiplikative Äquivalenz der $p_i$: Wenn 
$$M\cong R^\tilde{k}\oplus\bigoplus_{i=1}^\tilde{l}\bigoplus_{j=1}^{\tilde{m}_i}R/\tilde{p}_i^{\tilde{n}_{i,j}}R$$
eine gleichartige Zerlegung von M ist, so gilt $k=\tilde{k},l=\tilde{l}$ und es gibt eine eindeutige Permutation $\sigma\in S_l$ mit $p_i\sim\tilde{p}_{\sigma(i)},m_i\sim\tilde{m}_{\sigma(i)}$ und $n_{i,j}=\tilde{n}_{\sigma(i)}$.
Der Isomorphismus ist natürlich nicht eindeutig, so wie die Basis eines Vektorraumes nicht eindeutig bestimmt ist, sondern nur ihre Kardinalität.
## Siehe auch
- [Faktorringe](Einf.%20Alg/Definition/Faktorringe.md)
- [Faktormoduln](Einf.%20Alg/Definition/Faktormoduln.md)
- #EinfAlgVL9