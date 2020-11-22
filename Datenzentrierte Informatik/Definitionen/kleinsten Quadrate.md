# kleinsten Quadrate (least squares) #DataInf
Bei dem Betrachten von [unüberwachten Lernproblemen](Datenzentrierte%20Informatik/Definitionen/un%C3%BCberwachte%20Lernprobleme.md) wird folgender Fehlerwert definiert:
$$E=\frac{1}{n}\sum_{j=1}^n(y_j-\hat{y}_j)^2.$$
Es wird danach versucht diesesn zu minimieren. Die einzelnen Summanden werden auch ==Residuen== genannt.
##  univariate lineare Regression
Im Falle der [univariate lineare Regression](Datenzentrierte%20Informatik/Definitionen/univariate%20lineare%20Regression) wird dieser zu
$$E=\frac{1}{n}\sum_{j=1}^n(y_j-(w_0+w_1x_j))^2$$
## Siehe auch