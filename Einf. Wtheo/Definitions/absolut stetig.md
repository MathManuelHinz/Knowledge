# absolut stetig #EinfWth
- Eine Funktion F heißt ==absolut stetig==, falls $\exists\rho:\mathbb{R}\to\mathbb{R}$ [Borel](Einf.%20Wtheo/Definitions/Borel'sche%20sigma-Algebra.md) [messbar](Einf.%20Wtheo/Definitions/Messbare%20Funktionen%20und%20Zufallsvariablen.md) und [integrierbar](Einf.%20Wtheo/Definitions/Integral%20f%C3%BCr%20allgemeine%20Funktionen.md) bzg. Lebesgue, s.d.
$$F(t)-F(s)=\int_{s}^t\rho(x)dx$$
-  Eine Verteilung $\mathbb{P}$ ([Wahrscheinlichkeitsmaß](Einf.%20Wtheo/Definitions/Wahrscheinlichkeitsma%C3%9Fe.md) auf $\mathbb{R}$) mit ==absolut stetiger== Verteilungsfunktion F heißt auch eine absolut stetige Verteilung und $\rho$ heißt die ==Wahrscheinlichkeitsdichte== der W-Maß (oder Verteilung) $\mathbb{P}$ (wichtig: $\rho$ ist nicht eindeutig definiert.)
$$\mathbb{P}((s,t])=\int_s^t\rho(x)dx$$
-  Eine [Zufallsvariable](Einf.%20Wtheo/Definitions/Messbare%20Funktionen%20und%20Zufallsvariablen.md) X heißt ==absolut stetig== falls seine Verteilung $\mathbb{P}_x$ absolut stetig ist
$$\mathbb{P}(X\in(s,t])=\mathbb{P}_X((s,t])$$
und dann
$$\mathbb{E}[f(X)]=\int_\mathbb{R}f(x)\rho(x)dx$$
## Siehe auch
- #EinfWthVL7 