# Faktormoduln #EinfAlg 
Sei $R$ ein [Ring](Einf.%20Alg/Definition/Ring.md), $M$ ein R-[Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) und $N\subseteq M$ ein [Untermodul](Einf.%20Alg/Definition/Untermoduln.md).
## [Äquivalenzrelation](LA1/Definitions/%C3%84quivalenzrelation.md)
Wir schreiben $m_1\sim m_2 \iff m_1-m_2\in N$. Dies ist eine Äquivalenzrelation. Eine ==Nebenklasse von M in N== ist eine [Äquivalenzklasse](LA1/Definitions/Relationsklasse.md) bzgl. $\sim$. Sei $M/N$ die Menge der Nebenklassen. sei ==$\pi_{M,N}$== die Abb., welche jedem $m\in M$ seine Äquivalenzklasse zuordnet.
## Modulstruktur
Es gibt genau eine R-Modulstruktur auf  $M/N$ für die $\pi_{M,N}$ ein R[-Homomorphismus](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md) ist.  Für $\mu_1,\mu_2\in M/N$, $m_1,m_2\in M$ und $r\in R$:
$$\mu_1+\mu_2=\pi(m_1)+\pi(m_2)=\pi(m_1+m_2)$$
und
$$r\mu_1=r\pi(m_1)=\pi(rm_1)$$
## Fakt
$$\ker(\pi_{M,N})=N$$
## Siehe auch
- #EinfAlgVL7
- [Kern](Einf.%20Alg/Definition/Kern.md)