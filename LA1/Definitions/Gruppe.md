# Gruppe: #La1
Eine nichtleere Menge G heißt Gruppe wenn folgende Aussagen gelten:
### G1:
$\circ: G\times G\to G$ geschrieben $\circ (a,b)=a\cdot b=ab$
### G2:
$\forall_{a,b,c\in G}:(ab)c=a(bc)$ #Assoziativgesetz
### G3:
$\exists_{e\in G}$ mit $\forall_{a\in G}: ea=ae=a$ #Identität
### G4:
$\forall_{a\in G}\exists_{a^{-1}\in G}: a\times a^{-1}=a^{-1}\times a = e$ #Inverses
## Notation
Für $a \in G$ und $n\in \mathbb{Z}$ schreibe
$$a^n=\begin{cases}
\underbrace{a\cdot a \cdot ... \cdot a\cdot a}_{\text{n mal}} & n>0 \\
e & n=0\\
(a^{-1})^{|n|} & n<0
\end{cases}$$

## Beispiele
- $(\mathbb{R},+),(\mathbb{Q},+),(\mathbb{Z},+)$ sind [abelsche Gruppen](abelsche%20Gruppe) .
- Sei $X$ eine Menge. Dann ist $(X):= \{f: X\to X |\text{f bijektiv}\}$ mit der Verknüpfung $(f\circ g)(x):= f(g(x))$ eine Gruppe (Gruppe der Permutationen von X).
- Für $m\in\mathbb{N}^* (\mathbb{Z}_m,+_m)$ eine [abelsche Gruppe](abelsche%20Gruppe) (Gruppe der Restklassen).