# Integral für allgemeine Funktionen #EinfWth
Sei $f\geq 0$ [messbar](Einf.%20Wtheo/Definitions/Messbare%20Funktionen%20und%20Zufallsvariablen.md). Dann sei
$$\int_\Omega fd\mu:=\sup\limits_{g\leq f:g\in\mathscr{E}_+}\int_\Omega gd\mu\in\mathbb{R}_{\geq 0}\cup\{\infty\}.$$
Für allgemienn Funktionen können wir
$$f(\omega)=1_{f(\omega)\geq 0}f(\omega)+1_{f(\omega)< 0}f(\omega)$$
d.h. die Zerlegung von f in positive und negative Teile betrachten.
--------------------------------------
- Sei $f:\Omega\to\mathbb{R}$ messbar mit $\int_\Omega f_+d\mu<+\infty$ oder $\int_\Omega f_-d\mu<+\infty$. Dann
$$\int_\Omega fd\mu:=\int_\Omega f_+d\mu-\int_\Omega f_-d\mu.$$
- Eine messbare Funktion f heißt integrierbar, falls
$$\int_\Omega |f|d\mu=\int_\Omega f_+d\mu-\int_\Omega f_-d\mu<\infty.$$
- $L^1(\Omega,\mathscr{F},\mu)$ ist der Raum integirerbarer Funktionen (Vektorraum)
- $L^1(\Omega,\mathscr{F},\mu):=\{f:\Omega\to\mathbb{R}:$f messbar und $\int_\Omega |f|^pd\mu<+\infty\}$.
## Siehe auch
- #EinfWthVL5 