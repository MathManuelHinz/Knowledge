# Torsion #EinfAlg 
Sei R ein [Integritätsbereich](Einf.%20Alg/Definition/Integrit%C3%A4tsbereich.md). Für den R-[Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) m sei
$$M_{\text{Tor}}:=\{m\in M|\exists_{r\in R\setminus \{0\}}:rm=0\}$$
die Menge der ==Torsionselemente von M== oder ==die Torsion== oder ==der Torsionsteil von M==. M ist ==torsionsfrei== (bzw. ein ==Torsionsmodul==), falls $M_{\text{Tor}}=\{0\}$ bzw. ($M_{\text{Tor}}=M$) ist.
## Bemerkungen
- Es ist nötig, dass R ein Integritätsbereich ist (Siehe $R=\{0\}$).
- Mit $S=R\setminus\{0\}$ gilt $M_{\text{Tor}}=\ker(j:M\to M_S)$.
- Wenn M ein endlich [erzeugter](Einf.%20Alg/Definition/erzeugte%20Untermoduln.md) R-Torsionsmodul ist, gibt es $r\in R\setminus\{0\}$ mit $rM=0$.
- Für $R=\mathbb{Z}$, $M=\mathbb{Q}/\mathbb{Z}$ kann kein solches r gefunden werden.
- Wenn R ein [Noetherscher](Einf.%20Alg/Definition/Noethersche%20Ringe.md) Integritätsbereich und M ein endlich erzeugter R-Modul ist, so ist $M_{\text{Tor}}$ ein endlich erzeugter R-Modul, und es gibt ein  $r\in R\setminus\{0\}$ mit $rM_{\text{Tor}}=0$.
- Ein [Untermodul](Einf.%20Alg/Definition/Untermoduln.md) in einem Torsionsmodul ist wieder ein Torsionsmodul.
- Ein Untermodul in einem torsionsfreien Modul ist wieder torsionsfrei.
## Siehe auch
- #EinfAlgVL9 