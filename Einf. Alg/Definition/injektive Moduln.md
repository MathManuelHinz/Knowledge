# injektive Moduln #EinfAlg
Sei R ein beliebiger [Ring](Einf.%20Alg/Definition/Ring.md). Dann heißt ein R-[Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) M ==injektiv==, wenn die folgenden äquivalenten Bedingungen erfüllt sind:
- Sei I ein [Ideal](Einf.%20Alg/Definition/Ideal.md) in R, $\phi:I\to M$ ein [Morphismus von R-Moduln](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md), dann existiert $m\in M$ mit $\phi(i)=i\cdot m$ für alle $i\in I$.
- Sei T ein R-Modul, $X\subseteq T$ ein [Untermodul](Einf.%20Alg/Definition/Untermoduln.md), s.d. der R-Modul [$T/X$](Einf.%20Alg/Definition/Faktormoduln.md) endlich erzeugt ist und $\phi:X\to M$ ein Morphismus von R-Moduln. Dann existiert ein Morphismus $f:T\to M$ von R-Moduln mit $F_{|_X}=\phi$.
- Jede kurze [exakte Folge](Einf.%20Alg/Definition/Exakte%20Folgen.md) 
$$0\to M\to T\to Q\to 0$$ von -Moduln mit endlich erzeugtem Q [zerfällt](Einf.%20Alg/Definition/Zerfall%20und%20Spaltung%20von%20kurzen%20exakten%20Folgen.md).
## Bemerkung 
Man kann in der zweiten und dritten Bedingung die endliche Erzeugtheit aufgeben, wenn man das Zornsche Lemma anwendet.
## Siehe auch
- #EinfAlgVL11