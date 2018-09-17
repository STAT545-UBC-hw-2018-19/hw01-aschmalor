---
title: "Homework 1"
author: "Anita"
date: "September 14, 2018"
output:
  html_document:
    keep_md: yes
  pdf_document: default
  word_document: default
---


```
## -- Attaching packages ----------------------------------------------------------------- tidyverse 1.2.1 --
```

```
## v ggplot2 3.0.0     v purrr   0.2.5
## v tibble  1.4.2     v dplyr   0.7.6
## v tidyr   0.8.1     v stringr 1.3.1
## v readr   1.1.1     v forcats 0.3.0
```

```
## -- Conflicts -------------------------------------------------------------------- tidyverse_conflicts() --
## x dplyr::filter() masks stats::filter()
## x dplyr::lag()    masks stats::lag()
```


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


![](hw01_gapminder_files/figure-html/unnamed-chunk-4-1.png)<!-- -->![](hw01_gapminder_files/figure-html/unnamed-chunk-4-2.png)<!-- -->![](hw01_gapminder_files/figure-html/unnamed-chunk-4-3.png)<!-- -->

