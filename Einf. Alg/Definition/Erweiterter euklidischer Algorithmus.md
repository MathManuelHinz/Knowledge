# Erweiterter euklidischer Algorithmus #EinfAlg 
Wenn $\text{ggT}(a,b)=c$, dann $\exists p,q: pa+qb=c$ nach dem [Euklidischer Algorithmus](Einf.%20Alg/Definition/Euklidischer%20Algorithmus.md).
Wenn wir dann 

   a     |  b | q | s | t         
--- | --- | --- | --- | ---

mit $s_i=t_{i+1}$ und $t_i=s_{i+1}-q_i t_{i+1}$ von Unten einsetzen so bekommen mit s und t die behaupteten Werte.
## Beispiel
$\text{ggT}(128,34)=2$:

   a     |  b | q | s | t         
--- | --- | --- | --- | ---
128 | 34 | 3 | |
34 | 26 | 1 | |
26 | 8 | 3 | |
8 | 2 | 4 | |

Und dann 

   a     |  b | q | s | t         
--- | --- | --- | --- | ---
128 | 34 | 3 | 4 | -15
34 | 26 | 1 | -3 | 4
26 | 8 | 3 | 1 | -3
8 | 2 | 4 | 0 | 1

Insbesondere gilt dann $128*4-15*34=2$.

Mod N kann man so Inverse  mod N finden, da $\text{ggT}(a,N)=1$.

## Siehe auch
- [Euklidischer Algorithmus](Einf.%20Alg/Definition/Euklidischer%20Algorithmus.md)
- #Comment