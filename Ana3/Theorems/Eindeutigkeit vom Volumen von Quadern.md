# Eindeutigkeit vom Volumen von Quadern #Ana3
Sei [$\mathscr{Q}$](Quader.md) die Menge der Quader in $\mathbb{R}^n$ und sie $\nu:\mathscr{Q}\to[0,\infty]$ eine Abbildung mit folgenden Eigenschaften:
- $\forall_{a\in\mathbb{R}^n}\forall_{Q\in\mathscr{Q}}:\nu(a+Q)=\nu(Q)$ #Translationsinvarianz
- $\nu([0,1]^n)=1$ #Normierung
- falls ein Quader $Q$ die disjunkte Vereinigung von zwei Quadern $Q_1$ und $Q_2$ ist, so gilt $\nu(Q)=\nu(Q_1)+\nu(Q_2).$ #endlicheAdditivität 

Dann gilt schon $\nu(Q)=\text{Vol}(Q)$.