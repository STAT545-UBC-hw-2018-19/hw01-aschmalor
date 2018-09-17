---
title: "Homework 1"
author: "Anita"
date: "September 14, 2018"
output:
  html_document: 
    keep_md: yes
  word_document: default
---




```r
head(gapminder)
```

```
## # A tibble: 6 x 6
##   country     continent  year lifeExp      pop gdpPercap
##   <fct>       <fct>     <int>   <dbl>    <int>     <dbl>
## 1 Afghanistan Asia       1952    28.8  8425333      779.
## 2 Afghanistan Asia       1957    30.3  9240934      821.
## 3 Afghanistan Asia       1962    32.0 10267083      853.
## 4 Afghanistan Asia       1967    34.0 11537966      836.
## 5 Afghanistan Asia       1972    36.1 13079460      740.
## 6 Afghanistan Asia       1977    38.4 14880372      786.
```
Let's look at the population for each coountry and year

```r
head(gapminder$pop)
```

```
## [1]  8425333  9240934 10267083 11537966 13079460 14880372
```

Number of 'country-years' by continent.
*Note that each country is counted as many times as years that data from it exists.*

```r
table(gapminder$continent)
```

```
## 
##   Africa Americas     Asia   Europe  Oceania 
##      624      300      396      360       24
```

Histogram of the life expectancy
![](hw01_gapminder_files/figure-html/unnamed-chunk-5-1.png)<!-- -->

