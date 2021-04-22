# Monogene Erweiterungen und Ausdehnungen #EinfAlg 
Sei $L/K$ eine [algebraische](Einf.%20Alg/Definition/algebraische%20und%20transzendente%20Elemente.md) [Körpererweiterung](Einf.%20Alg/Definition/Endliche%20K%C3%B6rpererweiterung.md). Für $x\in L$ sei $K(x)$ das Bild der injektiven Abbildung
$$A_x:K[T]/\text{Min}_{x/K}K[T]\to L$$
$$P\text{ mod }\text{Min}_{x/K}\mapsto P(x)$$
Wir nennen $L/K$ ==monogen==, falls ein $x\in L$ mit $L=K(x)$ existiert. In diesem Fall nennen wir $x$ ein ==primitives Element== der Körpererweiterung.
## Fakt 1
$K(x)$ ist ein Unterkörper von L und zwar der kleinste Unterkörper von L, welcher $K\cup \{x\}$ enthält, oder auch der kleinste Unterring L mit dieser Eigenschaft.
## Fakt 2
Der Grad einer monogenen Erweiterung ist $[K(x):K]=\deg(x/K)$, der Grad des [Minimalpolynoms](Einf.%20Alg/Definition/Minimalpolynom.md).
## Ausdehnungen
Sei Hom die Menge der [Ringhomomorphismen](Einf.%20Alg/Definition/Ringhomomorphismus.md).
Jedes $\phi\in\text{Hom}(R,S)$ definiert ein Element $\phi_T\in \text{Hom}(R[T],S[T])$ durch 
$$\sum_{k=0}^\infty p_kT^k\mapsto\sum_{k=0}^\infty \phi(p_k)T^k.$$
Für einen [Körper](LA1/Definitions/K%C3%B6rper.md) $M$ und einen Ringhomomorphismus $\kappa:K\to M$ sei $\mathbb{A}_{L/K,\kappa}=\{\lambda \in \text{Hom}(L,M)|\lambda\vert_K=\kappa\}$
die Menge der ==Ausdehnung== von $\lambda$ auf L.
## Satz
Sei zusätzlich $L=K(x)/K$ eine monogene Erweiterung mit Primitivem Element $x$. Dann gibt es eine kanonische Bijektion zwischen $$\mathbb{A}_{L/K,\kappa}\cong\{m\in M|(\kappa_T\text{Min}_{x/K})(m)=0\}$$
$$\lambda\mapsto\lambda(x)$$
## Folgerung
Wenn in de obigen Situation L/K eine monogene Körpererweiterung ist, so gilt $$\#\mathbb{A}_{L/K,\kappa}\leq [L:K]$$
und für algebraisch abgeschlossenes M ist die Menge der Ausdehnungen nichtleer. 
## Siehe auch
- #EinfAlgVL16 