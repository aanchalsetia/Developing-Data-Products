---
title: "ReproPitch"
author: "Aanchal Setia"
date: "11/29/2020"
output:
  slidy_presentation: 
    keep_md: yes
  ioslides_presentation: default
---



## Diamond Analysis Report

Diamond Data Analysis Report enabled using shiny application.

## Application Overview

- Diamonds Properties can be analyzed using several Parameters.
- Carat,Price,sample size,color Depth are some of the common parameters.
- This application allows the user to pick the right parameters for the best Diamond selection.


## Link to Application

Click the Below Link for the Application.

https://aanchalsetia.shinyapps.io/shiny/



## Data Used
The data used for this application is diamonds data set in-built in R Studio. Containing information about 53940 diamonds with 10 variables.


```r
library("ggplot2")
head(diamonds)
```

```
## # A tibble: 6 x 10
##   carat cut       color clarity depth table price     x     y     z
##   <dbl> <ord>     <ord> <ord>   <dbl> <dbl> <int> <dbl> <dbl> <dbl>
## 1 0.23  Ideal     E     SI2      61.5    55   326  3.95  3.98  2.43
## 2 0.21  Premium   E     SI1      59.8    61   326  3.89  3.84  2.31
## 3 0.23  Good      E     VS1      56.9    65   327  4.05  4.07  2.31
## 4 0.290 Premium   I     VS2      62.4    58   334  4.2   4.23  2.63
## 5 0.31  Good      J     SI2      63.3    58   335  4.34  4.35  2.75
## 6 0.24  Very Good J     VVS2     62.8    57   336  3.94  3.96  2.48
```
