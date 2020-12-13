# Die allgemeine Jordansche Normalform #EinfAlg 
Sei V ein endlochdimensionaler K-[Vektorraum](LA1/Definitions/Vektorraum.md) und $A:V\to V$ ein [Endomorphismus](LA1/Definitions/lineare%20Abbildung.md)von V. Dann gibt es eine wiederholungsfreie Folge $(P_i)_{i=1}^l$ [irreduzibeler](Einf.%20Alg/Definition/irreduzibel.md) normierter [Polynome](Einf.%20Alg/Definition/Polynomring.md) $P_i\in K[T]$, eine Folge $(m_i)_{i=1}^l$ positiver ganzer Zahlen sowie eine Doppelfolge $(n_{i,j})_{i=1,j=1}^{l,m_i}$ positiver ganzer Zahlen mit $n_{i,1}\geq n_{i,2}\geq\dots\geq n_{i,m_i}$ und einen Isomorphismus 
$$V\stackrel{\cong}{\to}\bigoplus_{i=1}^l\bigoplus_{j=1}^{m_j}K[T]/P_i^{n_{i,j}}K[T]$$
s.d. das Diagramm
![](Res/Pasted%20image%2020201213125711.png)
kommutiert. Die Folgen bzw. Doppelfolgen sind bis auf Permutation in i eindeutig durch das Paar $(V,A)$ bestimmt.
## Siehe auch
- #EinfAlgVL12 