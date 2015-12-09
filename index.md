---
title       : A
subtitle    : a
author      : bbb
job         : ccc
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs    : {theme: simple, transition: cube}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : desert      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- 

## Read-And-Delete


```r
library(knitr)
kable(head(iris,10))
```



| Sepal.Length| Sepal.Width| Petal.Length| Petal.Width|Species |
|------------:|-----------:|------------:|-----------:|:-------|
|          5.1|         3.5|          1.4|         0.2|setosa  |
|          4.9|         3.0|          1.4|         0.2|setosa  |
|          4.7|         3.2|          1.3|         0.2|setosa  |
|          4.6|         3.1|          1.5|         0.2|setosa  |
|          5.0|         3.6|          1.4|         0.2|setosa  |
|          5.4|         3.9|          1.7|         0.4|setosa  |
|          4.6|         3.4|          1.4|         0.3|setosa  |
|          5.0|         3.4|          1.5|         0.2|setosa  |
|          4.4|         2.9|          1.4|         0.2|setosa  |
|          4.9|         3.1|          1.5|         0.1|setosa  |


--- 

## Slide 2


```r
coef(summary(lm(Sepal.Length~., iris)))
```

```
##                     Estimate Std. Error   t value     Pr(>|t|)
## (Intercept)        2.1712663 0.27979415  7.760227 1.429502e-12
## Sepal.Width        0.4958889 0.08606992  5.761466 4.867516e-08
## Petal.Length       0.8292439 0.06852765 12.100867 1.073592e-23
## Petal.Width       -0.3151552 0.15119575 -2.084418 3.888826e-02
## Speciesversicolor -0.7235620 0.24016894 -3.012721 3.059634e-03
## Speciesvirginica  -1.0234978 0.33372630 -3.066878 2.584344e-03
```



