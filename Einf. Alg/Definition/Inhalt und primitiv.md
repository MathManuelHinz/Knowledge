# Inhalt und primitiv #EinfAlg 
Sei R ein [Integritätsbereich mit ggT](Einf.%20Alg/Definition/Integrit%C3%A4tsbereich%20mit%20ggT.md).
Für ein [Polynom](Einf.%20Alg/Definition/Polynomring.md) $P=\sum_{i=0}^np_iT^i$ sei der ==Inhalt== von P definiert als $\text{ggT}(p_0,p_1,\dots)=\text{ggT}(p_0,p_1,\dots,p_i)$, wobei $i$ so gewählt ist, dass $p_j=0$ für $j>i$.
Ein solches Polynom wird (in der Vorlesungsreihe) ==primitiv== genannt, wenn $\text{Inh}(P)\sim 1$ ist.
## Bemerkungen 
- Wenn $P\in R[T]$ primitiv ist, so $P\neq0$.
- Wir haben $\text{Inh}(rP)\sim r\text{Inh}(P)$ für $r\in R$ und $P\in R[T]$.
- Wenn $P\in R[T]\setminus \{0\}$, so ist $\text{Inh}(P)\neq 0$ und $P=\text{Inh}(P)\tilde{P}$, wobei $\tilde{P}\in R[T]$ primitiv ist. Für $P=0$ gilt dasselbe mit $\tilde{P}=1$.
## Siehe auch
- #EinfAlgVL13 