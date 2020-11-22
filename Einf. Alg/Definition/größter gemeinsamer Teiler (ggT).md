# größter gemeinsamer Teiler (ggT) #EinfAlg 
Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md). Für $r\in R$ schreiben wir ==$r|a$== und sagen =="r teilt a"==, falls ein $q\in R$ mit $a=qr$ existiert. Man überzeugt sich leicht von der Transitivität der Teilbarkeits[relation](LA1/Definitions/Relation.md).
Sei nun R ein [Integritätsbereich](Einf.%20Alg/Definition/Integrit%C3%A4tsbereich.md). Ein größter gemeinsamer Teiler von $r_1,\dots r_k\in R$ ist ein $r\in R$ mit folgenden Eigenschaften:
- $r|r_i$ für alle $i$
- Sei $\rho\in R$ mit $\rho|r_i$ für alle i. Dann gilt schon $\rho|r$.
## Bemerkung
- In jedem Integritätsbereichist 1 ein ggT().
- In jedem Integritätsbereichist r ein ggT(r).
-  In jedem Integritätsbereichist 0 ein ggT$(0,\dots,0)$.
## Siehe auch