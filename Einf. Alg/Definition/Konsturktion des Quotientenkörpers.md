# Konsturktion des Quotientenkörpers #EinfAlg 
Sei R ein [Ring](Einf.%20Alg/Definition/Ring.md)
Sei K die Menge aller [Äquivalenzklassen](LA1/Definitions/Relationsklasse.md) $(r,s)$ mit $r\in R,s\in R\setminus \{0\}$ unter der [Äquivalenzrelation](LA1/Definitions/%C3%84quivalenzrelation.md)$$(r_1,s_1)\sim(r_2,s_2)\iff r_1s_2=r_2s_1.$$
Sei $[r,s]\in K$ die Äquivalenzklasse des Paares $(r,s)$.
Es gilt:
$$0_K=[0,1]=\{(0,s)|s\in R\setminus\{0\}\};$$
und
$$1_K=[1,1]=\{(s,s)|s\in R\setminus\{0\}\}.$$
Wir führen folgende Operationen ein:
$$[r_1,s_1]+[r_2,s_2]:=[r_1s_2+r_2s_1,s_1s_2];$$
$$[r_1,s_1]\cdot[r_1,s_1]=[r_1r_2,s_1s_2].$$
Des weiteren sei $i(r)=[r,1]$
## Siehe auch
- [Satz zu Integritätsbereichen und Körpern](Einf.%20Alg/Theorems/Satz%20zu%20Integrit%C3%A4tsbereichen%20und%20K%C3%B6rpern.md)