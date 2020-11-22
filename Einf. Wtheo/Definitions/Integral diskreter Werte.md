# Integral diskreter Werte #EinfWth
Sei $(\Omega,\mathscr{F},\mathbb{P})$ ein [Wahrscheinlichkeitsraum](Einf.%20Wtheo/Definitions/Wahrscheinlichkeitsma%C3%9Fe.md) und $f:\Omega\to\mathbb{R}$ eine Funktion, die nur N verschiedene Werte $x_1,\dots,x_N$ annimmt. Dann ist
$$\int_\Omega fd\mathbb{P}:=\sum_{k=1}^N x_k\mathbb{P}(\{\omega\in\Omega|f(\omega)=x_k\})$$
genau dann definiert wenn $f^{-1}(x_k)=\{\omega\in\Omega|f(\omega)=x_k\}\in\mathscr{F}$ für alle $k=1,\dots,N$.
## Siehe auch
- #EinfWthVL5