# Isomorphiesätze über Moduln #EinfAlg 
Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md).
## 1. Isomorphiesatz über Moduln
Seien $K\subseteq L\subseteq M$ [Untermoduln](Einf.%20Alg/Definition/Untermoduln.md) des R-[Moduls](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) M. Dann ist $L/K$ ein Untermodul von $M/K$, und es gibt genau einen Isomorphismus
$$\iota:M/L\to (M/K)/(L/K)$$
mit $\iota \pi_{M,L}=\pi_{M/K,L/K}\pi_{M,K}.$
![](Res/Pasted%20image%2020201121180008.png)
## 2. Isomorphiesatz über Moduln
Es seien $K,L$ Untermoduln des R-Moduls M. Dann sind $K\cap M$ und $k+L:=\{k+l|k\in K,l\in L\}$ Untermoduln von M und $K\subseteq K+L$ sowie $L\subseteq K+L$.  Sei $i:L\to K+L$ die Inklusion. Dann gibt es genau einen Isomorphismus
$$\iota:L/(K\cap L)\to(K+L)/K$$
mit  $\iota\pi_{L,K\cap L}=\pi_{K+L,K}i$.
![](Res/Pasted%20image%2020201121184345.png)
## 1. Isomorphiesatz für Ringe
Es seien $J\subseteq I$ [Ideale](Einf.%20Alg/Definition/Ideal.md) in dem Ring R. dann ist $I/J$ ein Ideal in dem Ring $R/J$ und es gibt genau einen Isomorphismus
$$\iota: R/I\to (R/J)/(I/J)$$
mit 
$\iota \pi_{R,I}=\pi_{R/J,I/J}\pi_{R,J}$.
![](Res/Pasted%20image%2020201121183801.png)
## Bemerkung analog zum 2. Isomorphiesatz (nun für Ringe)
Es seien R ein Ring und I, J Ideale in R. Nach dem zweiten Isomorphiesatz für Moduln haben wir einen Isomorphismus $J/I\cap J\cong (I+J)/I$.
## Siehe auch
- #EinfAlgVL7 
- [Faktormoduln](Einf.%20Alg/Definition/Faktormoduln.md)