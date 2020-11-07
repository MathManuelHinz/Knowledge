# Maßraum #Ana3
Ein Tripel $(X,S,\mu)$ ist ein Maßraum, und $\mu$ ein Maß auf $S$, falls $S$ eine [$\sigma$-Algebra](Ana3/Definitions/sigma-Algebra.md) auf X, $\mu S\to[0,\infty]$, und
- $\mu(\emptyset)$.
- $\mu$ $\sigma$-additiv ist, d.h. $A:\mathbb{N}\to S$ mit $A_h\cap A_k=\emptyset$ für alle $h\not =k$ gilt: $$\mu\left(\bigcup_{h\in\mathbb{N}}\right)=\sum_{h\in\mathbb{N}}\mu(A_h).$$

Eine Menge $N\subseteq M$ heißt Nullmenge falls $N\in S$ und $\mu(N)=0$. Der Maßraum heißt vollständig, falls jede Teilmenge M einer Nullmenge N eien Nullmenge ist.
## Bemerkung
- Falls $A$ und $B$ disjunkt sind, dann $\mu(A\cup B)=\mu(A)+\mu(B)$.
- Falls $A\subseteq B$, dann $\mu(A)\leq \mu(B)$.
## Beispiele
- Sei X eine nichtleere Menge. Dann ist $(X,\mathcal{P}(X),\#)$ ein Maßraum. Die einzige Nullmenge ist die leere Menge.
- Sei X eine nichtleere Menge, $\mu(\emptyset):=0,\mu(X):=1$. Dann ist $(X,\{\emptyset, X\}, \mu)$ ein Maßraum.
- Sei X eine nichtleere Menge $a\in X, \delta_\alpha:\mathcal{P}(X)\to [0,\infty]$, $$\delta_\alpha(E) :=\begin{cases}1 & \text{ falls } \alpha \in E,\\0 & \text{sonst.}\end{cases}$$ Dann ist $(X,\mathcal{P},\delta_\alpha)$ ein Maßraum. 
## Siehe auch
