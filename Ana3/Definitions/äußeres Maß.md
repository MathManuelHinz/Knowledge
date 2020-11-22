# äußeres Maß #Ana3
Sei X eine nichtleere Menge. Die Abbildung $\mu^*:\mathcal{P}(X)\to[0,\infty]$ heißt äußeres Maß auf X falls
- $\mu^*(\emptyset)=0$;
- Monotonie: falls $A\subseteq B\subseteq X$, dann $\mu^*(A)\leq\mu^*(B)$;
- $\sigma$-Subadditivität: für alle Folgen $A:\mathbb{N}\to\mathcal{P}(X)$ gilt: $$\mu^*\left(\bigcup_{h\in\mathbb{N}}A_h\right)\leq\sum_{h\in\mathbb{N}}\mu^*(A_h).$$
## Beispiele
- $\mu_0^*:\mathcal{P}\to[0,\infty],\mu^*(A):=0.$
- $\mu_1^*:\mathcal{P}\to[0,\infty],\mu_1^*(A):=\begin{cases}0&\text{falls }A=\emptyset\\1&\text{sonst}\end{cases}.$
- $\mu_2^*:\mathcal{P}\to[0,\infty],\mu_2^*(A):=\#A.$
- Sei $(X,d)$ ein [metrischer Raum](metrischer%20Raum.md), $\mu_3^*:\mathscr{P}\to[0,\infty],\mu_3^*:=\begin{cases}0&\text{falls }A=\emptyset\\\sup\{d(a,x_0):a\in A\}&\text{sonst}\end{cases}.$
## Siehe auch
