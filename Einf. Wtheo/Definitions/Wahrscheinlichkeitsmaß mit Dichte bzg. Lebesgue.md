# Wahrscheinlichkeitsmaß mit Dichte bzg. Lebesgue #EinfWth
Sei $\rho:\mathbb{R}\to\mathbb{R}_+$ eine positive [messbare Funktion](Einf.%20Wtheo/Definitions/Messbare%20Funktionen%20und%20Zufallsvariablen.md) mit
$$\int_\mathbb{R}\rho(x)dx=1.$$
Dann, ist ein [Wahrscheinlichkeitsmaß](Einf.%20Wtheo/Definitions/Wahrscheinlichkeitsma%C3%9Fe.md) $\mathbb{P}$ auf $\mathbb{R},\mathscr{B}(\mathbb{R})$ definiert durch:
$$\mathbb{P}(A):=\int_A\rho(x)dx=\int_\mathbb{R}\mathbb{1}_{A}(x)\rho(x)dx, A\in\mathscr{B}(\mathbb{R}).$$
Wir nennen $\mathbb{P}$ W-Maß mit Dichte $\rho$ bzgl. Lebesgue. Die Verteilungsfunktion F von $\mathbb{P}$ ist 
$$F(t)=\int_{-\infty}^t\rho(x)dx.$$
Falls $\rho$ stetig ist, dann ist F eine stetige differenzierbare Funktion mit $F'=\rho$.
## Siehe auch
- #EinfWthVL7 