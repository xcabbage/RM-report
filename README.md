---
title: "A demo R+markdown document"
author: "Gergely Daroczi"
date: '2016-02-03'
output: html_document
runtime: shiny
---

Markdown is a simple markup language to format plain text files, eg using *italic* or **bold** font, or sometimes even ***both*** or ~~none~~ at all. We can also refer to inline `code` examples, or use syntax highlighting for larger code chunks:

```r
n <- 100
x <- rpois(n, 10)
summary(x)
hist(x)
```

But we can also evaluate `r "R"` code inline or in separate code chunks as well:

```{r}
n <- 100
x <- rpois(n, 10)
summary(x)
hist(x)
```
