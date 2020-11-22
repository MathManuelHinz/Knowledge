# Euklidischer Algorithmus #EinfAlg 
Sei R ein [Euklidischer Ring](Einf.%20Alg/Definition/Euklidischer%20Ring.md) und E wie in der Definition dieses Begriffes. Man kann dann $\text{ggT}(r_1,r_2)$ iwe folgt bestimmten. Falls $r_i=0$ für $1\leq i\leq 2$ ist $r_{3-i}$ ein $\text{ggT}(r_1,r_2)$. Andernfalls bestimmen wir $r_i$ für $r_i>2$ als Rest bei der Division von $r_{i-2}$ durch $r_{i-1}$ mit Rest für $q,r_i\in R$:
$$r_{i-2}=qr_{i-1}+r_i,$$
wobei im Fall $r_i=0$ das Verfahren mit $\text{ggT}(r_1,r_2)=r_{i-1}$ abbricht. 
## Folgerungen
- Das Verfahren bricht in der Tag immer ab.
## Siehe auch
## Vorlesung
#EinfAlgVL5