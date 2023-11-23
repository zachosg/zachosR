## zachosR
**dat=mtcars**

*pcars=scale(dat)*

*p=dist(pcars)
* c=hclust(p,method = "ward.D2")
* plot(c)
* rect.hclust(c,k=4)

