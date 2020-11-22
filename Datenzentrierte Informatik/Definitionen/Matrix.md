# Matrix #DataInf
$X\in\mathbb{R}^{m\times n}$ ist eine Matrix mit $mn$ Elementen $x_{ij}\in\mathbb{R}$.
$$X=\begin{bmatrix}x_{11}&x_{12}&\dots&x_{1n}\\
x_{21}&x_{22}&\dots&x_{2n}\\
\vdots&\vdots&\ddots&\vdots\\
x_{m1}&x_{m2}&\dots&x_{mn}\end{bmatrix}$$
## Eigenschaften:
- X ist ==breit==, wenn $m<n$
- X ist ==hoch==, wenn $m>n$
- X ist ==quadratisch==, wenn $m=n$
- $(X^\intercal)_{ij}=(X)_{ji}$
- X ist ==symmetrisch==, wenn $X=X^\intercal$
- X,Y Matrizen mit $X\in\mathbb{R}^{m\times k},Y\in\mathbb{R}^{k\times n}$, dann $XY=Z\in\mathbb{R}^{m\times n}$ mit $z_{ij}=\sum_{l=1}^kx_{il}y_{lj}$
- $X^{-1}$ ==inverse Matrix== zu X, wenn $XX^{-1}=X^{-1}X=I$, falls X ==invertierbar==.
## Siehe auch
- #DataInfVL4 