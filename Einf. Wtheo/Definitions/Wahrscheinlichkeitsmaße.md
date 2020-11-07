# Wahrscheinlichkeitsmaße #EinfWth
 Sei $(\Omega,\mathscr{F})$ ein [Messraum](Einf.%20Wtheo/Definitions/sigma-Algebra.md) und $\mathbb{P}:\mathscr{F}\to\mathbb{R}_{\geq0}$ eine Abbildung mit
 - $\mathbb{P}(\Omega)=1$ #Normierung 
 - $\mathbb{P}(\emptyset)=0$
 - Falls $A_n\in\mathscr{F},n\geq 1$ sind paarweise disjunkt, dann 
 $$\mathbb{P}\left(\bigcup_{n \geq 1}A_n\right)=\sum_{n\geq 1}\mathbb{P}(A-n).$$ #sigmaAdditivität
 Dann ist $\mathbb{P}$ ein Wahrscheinlichkeitsmaß auf $(\Omega,\mathscr{F})$. Das Tripel $(\Omega,\mathscr{F},\mathbb{P})$ heißt dann Wahrscheinlichkeitsraum.
## Siehe auch