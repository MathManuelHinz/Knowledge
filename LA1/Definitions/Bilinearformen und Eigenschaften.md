# Bilinearformen und Eigenschaften #La1 
Sei $V$ ein K-[Vektorraum](Vektorraum.md) und $f:V\times V\to K$. $f$ heißt Bilinearform auf V, falls f in jedem Argument K-linear ist:
- $\forall_{x\in V}f(x,\cdot):V\to K$ ist linear.
- $\forall_{x\in V}f(\cdot,x):V\to K$ ist linear.
## Symmetrie
Eine Bilinearform heißt $f$ symmetrisch, falls 
- $\forall_{x,y\in V}f(x,y)=f(y,x)$.
## Sesquilinearität
Ist K=$\mathbb{C}$, so heißt $f:V\times V\to K$ sesquilinear, falls für alle $x,y,z\in V$ und $\lambda,\mu\in\mathbb{C}$:
- $f(x,\lambda y+\mu z)=\lambda f(x,y)+\mu f(x,z)$.
- $f(\lambda x+\mu y,z)=\bar{\lambda} f(x,z)+\bar{\mu}f(y,z)$.
## Hermitesch
Ist K=$\mathbb{C}$, so heißt eine Bilinearform f hermitesch, falls 
- $\forall_{x,y\in V}f(x,y)=\overline{f(y,x)}$.
## Positiv (semi)-definit
Ist K=$\mathbb{C}$ oder $\mathbb{R}$ und f eine hermitische Sesquilinearform (oder das Analog in $\mathbb{R}$). f heißt positiv semidefinit falls
- $\forall_{x\in V}f(x,x)\geq 0$
und positiv definit falls zusätzlich
- $f(x,x)=0\iff x=0$.