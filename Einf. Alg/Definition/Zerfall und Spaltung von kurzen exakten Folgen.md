# Zerfall und Spaltung von kurzen exakten Folgen #EinfAlg
Für kurze [exakte Folgen](Einf.%20Alg/Definition/Exakte%20Folgen.md) von R-[Modul](Einf.%20Alg/Definition/Moduln%20%C3%BCber%20Ringen.md) der Art $$0\stackrel{}{\longrightarrow}M'\stackrel{i}{\longrightarrow}M\stackrel{p}{\longrightarrow}M''\stackrel{}{\longrightarrow} 0$$ 
sind die folgenden Bedingungen äquivalent (Morphismus hier = [Morphismus von R-Moduln](Einf.%20Alg/Definition/Morphismus%20von%20R-Moduln.md)):
- Es existiert einen Morphismus $\pi:M\to M'$, der linksinvers zu i ist, also $\pi i=\text{Id}_{M'}$.
- Es gibt einen Untermodul $X\subseteq M$, der durch p isomorph auf $M''$ abgebildet wird.
- Es gibt einen #toFix Morphismus $\sigma:M''\to M$ der rechtsinvers zu p ist, also $p\sigma=\text{Id}_{M''}$
![](Res/Pasted%20image%2020201128100706.png) 
- Es gibt einen Isomorphismus $\mu:M\to M'\oplus M''$ s.d. das Diagramm kommutiert:
![](Res/Pasted%20image%2020201205073658.png)

Eine kurze exakte Folge ==zerfällt== oder ==spaltet==, wenn diese äquivalenten Bedingungen erfüllt sind. Von jedem der unter A,B,C betrachteten Objekte $\pi,X,\sigma$ sagt man, dass es eine Spaltung der exakten Folge definiert.
## Beispiel
Wenn M, N R-Moduln sind, so ist
$$0\stackrel{}{\longrightarrow}M\stackrel{m\mapsto (m,0)}{\longrightarrow}M\oplus N\stackrel{(m,n)\mapsto n}{\longrightarrow}N\stackrel{}{\longrightarrow} 0$$ 
eine spaltende kurze exakte Folge.
## Siehe auch
- #EinfAlgVL8 
- #EinfAlgVL10 