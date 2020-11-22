# univariate nichtlineare Regression #DataInf
Gegeben sei eine Menge 
$$\{(x_j,y_j)\}_{j=1}^n$$
von Datenpunkten, wobei $x_j,y_j\in \mathbb{R}$ sind.
Wenn diese Daten keine lineare Struktur haben können wir z.B. ein ==polynomielles Modell== annehmen.
$$y_j=w_0+w_1x+w_2x^2+x_3x^3+\epsilon_j.$$
 Wir betrachten die 4-dimensionalen Vektoren
 $w=\begin{bmatrix}w_0\\w_1\\w_2\\w_3\end{bmatrix}$ und $\varphi_j=\begin{bmatrix}1\\x_j\\x_j^2\\x_j^3\end{bmatrix}$ und den n-dimensionalen Vektor $y=\begin{bmatrix}y_1\\\vdots\\y_n\end{bmatrix}$.
 Sei nun wieder $\Phi=\begin{bmatrix}\varphi_1&\dots\varphi_n\end{bmatrix}$ und es folgt:
 $$\hat{w}=\text{argmin}_{w}\Vert \Phi^\top w-y \Vert^2$$
und damit wieder
$$\hat{w}=(\Phi\Phi^\top)^{-1}\Phi y.$$
Mit numpy:
![](Res/Pasted%20image%2020201121200957.png)
## Siehe auch
- #DataInfVL5 