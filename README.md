---
title: "A demo R+markdown document"
author: "Gergely Daroczi"
date: '2016-02-03'
output: html_document
runtime: shiny
---
# static doc, prev lesson was server by server
Markdown is a simple markup language to format plain text files, eg using *italic* or **bold** font, or sometimes even ***both*** or ~~none~~ at all. We can also refer to inline `code` examples, or use syntax highlighting for larger code chunks:

```r
n <- 100
x <- rpois(n, 10)
hist(x)
```

But we can also evaluate `r "R"` code inline or in separate code chunks as well:

```{r}
n <- 100
x <- rpois(n, 10)
summary(x)
hist(x)
```


Shiny -- U can push to a server (need to install shiny server or shiny cloud)
Ui and server file
server - for the background
file /new proj/shiny web app
