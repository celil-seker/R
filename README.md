# R
R eğitimi
---
title: "R Notebook"
output: html_notebook
---

# yorum satırı ekelemek için kullanılır.

# ctrl+alt+I yeni kod yazımı için ekler.


## Operatörler

### Atama operatorleri

```{r}
# =
#  <-
#  <<-

celil <- 1
celil
celil = 9
celil
```
### Aritmetik Operatorler

```{r}
# Operator Tanimlari
#+	ekleme
#-	cikarma
#*	carpma
#/	bolme
#^ ya da **	ust alma

9*9
cel <- 9
cess <- 8
cel/cess
```

## Matematiksel Islemler

```{r}
#hesap makinesi olarak R
#*, +, -, /, ^
#sqrt
#abs
#log, log10, log2
sqrt(9)
abs(-19)
celil <- sqrt(9)
seker <- log(celil)
cese <- log2(seker)
log2(log(sqrt(9)))


```

## Temel Fonksiyonlar

```{r}

sessionInfo()
dir()
file.exists("R anlatim.Rmd")
ls()
rm("celil"
