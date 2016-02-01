---
title: "very) short introduction to R & ToDo answers"
output: html_document
author:
- Mosen Chegzade
date: "Jan 29, 2016"
---


# A short introduction
In this assignment I will be learning how to start coding in R and using R studio. I have used the pdf A [(very) short
introduction to R](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf) by 
Paul Torfs & Claudia Brauer. In this pdf they will described the basic funcionality of R and the use of it also it gives an opportunity to learn R by  doing the ToDo's in this document.

------------------

# Todo 1
```{r}
((2016-2014)/(2016-1994))*100
```


# Todo 2
```{r}
a <- 2016-2014
b <- (2016-1994)
b <- a / b
b <- (b * 100)
b
```

# Todo 3
```{r}
x <- c(4,5,8,11)  
sum(x)
```
# Todo 4
```{r}
x = rnorm(100)
plot(x)
```
# Todo 5
```{r}
help(sqrt)
```
# Todo 6
```{r}
source("~/Desktop/firstscript.R")
source("~/Desktop/firstscript.R")
```

# Todo 7
```{r}
p <- c(31:60)
Q=matrix(data=c(31:60),ncol=5,nrow=6)
```
# Todo 8
```{r}
v=data.frame(x = c(1:100), y = c(1:100), z = c(1:100))
v
```
# Todo 9
```{r}
help("rgb")
```
# Todo 10
```{r}
d = data.frame(a = c(3,4,5),b = c(12,43,54))
write.table(d,file="txt1.txt",row.names=FALSE)
d2 = read.table(file="txt1.txt",header=TRUE)
```

# Todo 11
```{r}
c=data.frame=c(1:100,1)
c^2
```
# Todo 12
```{r}
data=strptime( c("20140706080000","20165704000000"),format="%Y%m%d%H%M%S")
data=x
plot(x)
```
# Todo 13
This todo didn't compile 

### Sources used for this assignment:

[nicercode github](http://nicercode.github.io/guides/reports/)

[Kbroman.org markdown](http://kbroman.org/knitr_knutshell/pages/markdown.html)

[R markdown cheat sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)

[rmarkdown Rstudio](http://rmarkdown.rstudio.com/)


