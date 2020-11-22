# Beispiele von Zufallsvariablen #EinfWth
## Diskrete Verteilung
Sei $(\Omega,\mathscr{F},\mathbb{P})$ mit $\Omega$ diskret (d.h. abzählbar), $\mathscr{F}=\mathcal{P}(\Omega)$ und $\mu$ Zahlmaß, d.h. $\mu(\{\omega\})=1$ für alle $\omega\in\Omega$. Für $f:\Omega\to\mathbb{R}$ [integrierbar](Einf.%20Wtheo/Definitions/Integral%20f%C3%BCr%20allgemeine%20Funktionen.md) bzg. $\mu$ bezeichnen wir 
$$\sum_{\omega\in\Omega}f(\omega)=\int_\Omega f(\omega)\mu(d\omega).$$
Sei $\rho:\Omega\to\mathbb{R}_{\geq0}$ s.d.
$$\sum_{\omega\in\Omega}\rho(\omega)=1.$$
Dann 
$$\mathbb{P}(A):=\sum_{\omega\in A}\rho(\omega)$$
ist ein [Wahrscheinlichkeitsmaß](Einf.%20Wtheo/Definitions/Wahrscheinlichkeitsma%C3%9Fe.md) auf $(\Omega,\mathscr{F})$, s.d. $\mathbb{P}(\{\omega\})=\rho(\omega)$. Alle W-maße auf  $(\Omega,\mathscr{F})$ haben diese Form. Wir nennen $\rho$ die (diskrete) ==Dichte== von $\mathbb{P}$ bzgl. $\mu$.
----------------------------------------------
Im folgenden sei $\Omega=\mathbb{R}$ und $\mathscr{F}=\mathscr{B}(\mathbb{R})$.
## Dirac-Mass $\delta_{x}$
Das Dirac-Mass $\delta_{x}$ an $x\in\mathbb{R}$ ist definiert durch
$$\delta_{x}(A)=\mathbb{1}_{x\in A}.$$
Die Verteilungsfunktion von $\delta_{x_0}$ ist
$$F(x)=\delta_x(\{y\in\mathbb{R}:y\leq x\})=\begin{cases}1,&x\geq x_0\\
0,& x< x_0
\end{cases}$$
## Bernoulli Verteilung: Ber(p)
Die Bernoulli Verteilung mit Parameter $p\in[0,1]$, Ber(p) ist gegeben durch
$$\text{Ber}(p)=p\delta_1+(1-p)\delta_0.$$
## Binomialverteilung: Bin$(n,p)$
$$B_{n,p}=\sum_{k=0}^n \begin{pmatrix}n\\k\end{pmatrix}p^k(1-p)^{n-k}\delta_k$$
ist die Bin$(n,p)$ Verteilung mit Erwartungswert $np$.
## Poisson Verteilung: Poi$(\lambda)$
Sei $\lambda>0$. Die Poisson Verteilung mit Parameter $\lambda$ ist gegeben durch
$$\text{Poi}(\lambda):=\sum_{k\geq 0}\frac{\lambda^k}{k!}e^{-\lambda}\delta_k$$
Der Erwartungswert ist $\lambda$.
## Geometrische Verteilung: Geo$(q)$
Sei $q\in[0,1)$. Dann ist die Geometrische Verteilung mit Parameter $q$ durch $$\text{Geo}(q):=\sum_{n\geq 0}(1-q)q^n\delta_n$$
gegeben.
## Gleichverteilung
Sei $I=[a,b]\subset \mathbb{R}$. Dann ist die ==Gleichverteilung auf I== gegeben durch
$$d\mathbb{P}(x)=\frac{1}{b-a}1_{x\in [a,b]}dx$$
## Exponentialverteilung: Exp($\lambda$)
Die Exponentialverteilung mit Parameter $\lambda>0$ hat W-dichte
$$\rho(x)=\lambda e^{-\lambda x}\mathbb{1}_{x>0}.$$
Diese ist wichtig in Markov Ketten in stetiger Zeit.
## Gaussverteilung $\mathcal{N}(m,\sigma^2)$
Sei $m\in\mathbb{R},\sigma^2>0$. Die Gaussverteilung hat W-dichte
$$\rho(x)=\phi_{m,\sigma^2}(x)=\frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{(x-m)^2}{2\sigma^2}}$$
Der Erwartungswert ist $m$.
## Cauchy-Verteilung, Cauchy(a)
Die Cauchy-Verteilung mit Parameter a hat Dichtefunktion
$$\rho(x)=\frac{a}{\pi}\frac{1}{a^2+x^2}.$$
Diese Verteilung hat keinen Mittelwert.
## Siehe auch
- #EinfWthVL7