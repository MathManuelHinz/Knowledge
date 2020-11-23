# binäre lineare Klassifikatoren #DataInf
## Szenario
Gegeben sei eine annotierte Stichprobe
$$\{(x_j,y_j)\}_{j=1}^n$$
wobei die Datenpunkte $x_j\in\mathbb{R}^m$ aus zwei Klassen $\Omega_1,\Omega_2$ stammen und 
$$y_j=\begin{cases}+1&\text{if } x_j\in\Omega_1\\-1&\text{if } x_j\in\Omega_2\end{cases}.$$
Gesucht ist $f:\mathbb{R}^n\to\{-1,1\}^n$.
## Lösung
Seien nun wie üblich 
$$\varphi=\begin{bmatrix}1\\x\end{bmatrix},w=\begin{bmatrix}-b\\a\end{bmatrix}$$
und dann
$$h(x)=\varphi^\top w.$$
Wir lösen das [kleinsten Quadrate](Datenzentrierte%20Informatik/Definitionen/kleinsten%20Quadrate.md) Problem:
$$\hat{w}=\arg\min_w\sum_{j=1}^n\left(\varphi_j^\top w-y_j\right)^2$$
Wir schreiben dann wieder:
$$\Phi=\begin{bmatrix}
		|&|&&|\\
		\varphi_1&\varphi_2&\dots&\varphi_n\\
		|&|&&|
	   \end{bmatrix}$$
und 
$$y=\begin{bmatrix}y_1\\\vdots\\y_n\end{bmatrix}$$
und bekommen das äquivalente Problem:
$\hat{w}=\arg\min_w\Vert \Phi^\top w-y\Vert^2$
und damit wieder
$$\hat{w}=(\Phi\Phi^\top)^{-1}\Phi y.$$
Mit numpy:
![](Res/Pasted%20image%2020201123193706.png)
## Anwendbarkeit:
Lineare Klassifikatoren können genau dann fehlerfrei funktionieren, wenn die betrachteten Klassen [linear separierbar](Datenzentrierte%20Informatik/Definitionen/linear%20separierbar.md) sind.
## Siehe auch
- [binärer Klassifikator](Datenzentrierte%20Informatik/Definitionen/bin%C3%A4rer%20Klassifikator.md)
- [univariate lineare Regression](Datenzentrierte%20Informatik/Definitionen/univariate%20lineare%20Regression.md)
- #DataInfVL6 