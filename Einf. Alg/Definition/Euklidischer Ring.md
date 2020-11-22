# Euklidischer Ring #EinfAlg 
Ein Euklidischer Ring ist ein [Integritätsbereich](Einf.%20Alg/Definition/Integrit%C3%A4tsbereich.md) R, s.d. eine Funktion $E:R\setminus\{0\}\to\mathbb{N}$ mit folgenden Eigenschaften existiert:
- Für $a,b\in R\setminus\{0\}$ gilt $E(ab)\geq E(a)$.
- Falls $d\in R\setminus\{0\}$ so hat jedes $x\in R$ eine Darstellung $$x=qd+r$$ mit $r=0$ oder $E(r)<E(d)$.
## Bemerkung
Der Terminus Euklidischer Ring wird leider nicht ganz einheitlich verwendent.
## Beispiele
- Für $R=\mathbb{Z}$ kann $E(a)=|a|$ genommen werden.
- Für einen [Körper](LA1/Definitions/K%C3%B6rper.md) K und $R=K[T]$ kann $E(P)=\deg P$ genommen werden.
## Siehe auch