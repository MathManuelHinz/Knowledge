# Vektorraum #La1 
Sei K ein [Körper](K%C3%B6rper.md). Ein Vektorraum über K besteht aus
- (V0) Einer additiv geschriebenen [abelschen Gruppe](abelsche%20Gruppe.md) $V$.
- (V1) Es gibt eine äußere Verknüpfung (skalare Multiplikation)$$\cdot:K\times V\to V,$$ so dass folgende Eigenschaften für alle $\lambda,\mu\in K$ und $x,y\in V$ erfüllt sind: 
	- (SM1) $\lambda(x+y)=\lambda x+\lambda y$ sowie $(\lambda+\mu)x=\lambda x+\mu x$ #Distributivgesetz 
	- (SM2) $(\lambda\mu)x=\lambda(\mu x)$ #Assoziativgesetz 
	- (SM3) $1_K x=x$ #Identität 
Die Elemente von V werden Vektoren genant, die Elemente von  K Skalare.

## Beispiele
- Der Nullraum $V=\{0\}$.
- $K^n=\underbrace{K\times \dots\times K}_{\text{n mal}}=\left\{v=\begin{pmatrix}v_1\\\vdots\\v_n\end{pmatrix}\Huge|\normalsize v_1,\dots,v_n\in K\right\}$ mit den offensichtlichen Operationen.
- Eine Allgemeine Konstruktion: Sei $(K,+,\cdot)$ ein [Körper](K%C3%B6rper.md), $(R,+,*)$ ein [Ring](Ring.md) und $\phi$ ein [Ringhomomorphismus](Ringhomomorphismus.md). Dann ist $R$ ein $K$ Vektorraum mit $+$ und $k\cdot r=\phi(k)*r$ als Skalarmultiplikation.