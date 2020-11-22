# univariate lineare Regression #DataInf
## Szenario
Gegeben sei eine Menge 
$$\{(x_j,y_j)\}_{j=1}^n$$
von Datenpunkten, wobei $x_j,y_j\in \mathbb{R}$ sind.
Es wird versucht den Zusammenhang $y_j=f(x_j)$ durch eine lineare Approximation von f darzustellen: $f(x_j)=w_0+w_1x_j$.
## Exakte Darstellung
Hier bekommen wir die exakte Darstellung
$$y_j=w_0+w_1x_j+\epsilon_j.$$
## Modellanpassungsproblem
$$\hat{w_0},\hat{w_1}=\text{argmin}_{w_0,w_1}\frac{1}{n}\sum_{j=1}^n(y_j-(w_0+w_1x_j))^2$$
Lösung des Problems durch "ableiten und zu Null setzen".
- $\nabla E=\begin{bmatrix}\frac{\partial E}{\partial w_0}\\ \frac{\partial E}{\partial w_1}\end{bmatrix}=0$ also [Gradient](Ana2/Gradient.md)$=0$.
- Daraus ergeben sich 2 Gleichungen, diese durch Einsetzten auflösen.
- $$\hat{w}_1=\frac{\sum_{j=1}^ny_jx_j-n\bar{y}\bar{x}}{\sum_{j=1}^n x_j^2-n\bar{x}^2}=\frac{\sum_{j=1}^n(x_j-\bar{x})(y_j-\bar{y})}{\sum_{j=1}^n (x_j-\bar{x})^2}$$
- $$\hat{w}_0=\bar{y}-\hat{w}_1\bar{x}$$
## Code Beispiel
![](Res/Pasted%20image%2020201109205624.png)
![](Res/Pasted%20image%2020201109205642.png)
## rabbit hole
$\hat{w}=\begin{bmatrix}\hat{w}_0\\\hat{w}_1\end{bmatrix}$ $X=\begin{bmatrix}1&1&\dots&1\\x_1&x_2&\dots&x_n\end{bmatrix}$ $y=\begin{bmatrix}y_1\\y_2\\\vdots\\y_n\end{bmatrix}$
Es folgt die Lösung
$$\hat{w}=(XX^\top)^{-1}Xy$$
## Für Profis...
Sei$w=\begin{bmatrix}w_0\\w_1\end{bmatrix}$ und $\varphi_j=\begin{bmatrix}1\\x_j\end{bmatrix}$. Dann folgt
$$E(w)=\sum_{j=1}^n\left(w^\top\varphi_j-y_j\right)^2=
\sum_{j=1}^n\left(\varphi_j^\top w-y_j\right)^2$$
Für $v=\begin{bmatrix}\varphi_1^\top w\\\varphi_1^\top w\\\vdots\\\varphi_n^\top w\end{bmatrix}$ und  $y=\begin{bmatrix}y_1\\y_2\\\vdots\\y_n\end{bmatrix}$ gilt dann
$$E(w)=\sum_{j=1}^n(v_j-y_j)^2=\Vert v-y\Vert^2.$$
Sei nun 
$$\Phi=\begin{bmatrix}
		|&|&&|\\
		\varphi_1&\varphi_2&\dots&\varphi_n\\
		|&|&&|
	   \end{bmatrix}$$
Wir erkennen $v=\Phi^\top w$. D.h.
$$\hat{w}=\text{argmin}_{w} E(w)=\text{argmin}_{w}\Vert \Phi^\top w-y \Vert^2$$
Es folgt:
$$\hat{w}=(\Phi\Phi^\top)^{-1}\Phi y$$
Wobei für $\Psi=\Phi^\top$: $\hat{w}=(\Psi\top\Psi)^{-1}\Psi^\top y$
mit $(\Psi\top\Psi)^{-1}\Psi^\top$ die ==(Moore-Penrose) Pseudoinverse== und der ==Prädiktions-/Hut-matrix== $H=\Psi(\Psi\top\Psi)^{-1}\Psi^\top$, da $\hat{y}=Hy$. Mit numpy:
![](Res/Pasted%20image%2020201121192454.png)
## Siehe auch
- #DataInfVL3
- #DataInfVL5