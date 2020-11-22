# multivariate lineare Regression #DataInf
## Szenario
Gegeben sei eine Menge 
$$\{(x_j,y_j)\}_{j=1}^n$$
von Datenpunkten, wobei $x_j\in \mathbb{R^2},y_j\in \mathbb{R}$ sind.
Es wird versucht den Zusammenhang $y_j=f(x_j)$ durch eine multilineare Approximation von f darzustellen: $f(x_j)=w_0+w_1x_{1j}+w_2x_{2j}$.
Seien nun $w=\begin{bmatrix}w_0\\w1\\w_2\\\end{bmatrix}$ und $\varphi_j=\begin{bmatrix}1\\x_{1j}\\x_{2_j}\\\end{bmatrix}$ 3-dimensionale Vektoren und 
$y=\begin{bmatrix}y_1\\\vdots\\y_n\end{bmatrix}$ ein n-dimensionaler Vektor. Sei nun wieder $\Phi=\begin{bmatrix}\varphi_1&\dots\varphi_n\end{bmatrix}$ eine $3 \times n$ [Matrix](Datenzentrierte%20Informatik/Definitionen/Matrix.md). Dann folgt:
$$\hat{w}=\text{argmin}_{w}\Vert \Phi^\top w-y \Vert^2$$
und damit wieder
$$\hat{w}=(\Phi\Phi^\top)^{-1}\Phi y.$$
Mit numpy:
![](Res/Pasted%20image%2020201121194100.png)
## Siehe auch
- #DataInfVL5 