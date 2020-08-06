---
title: "Script"
author: "Ousman"
date: "8/5/2020"
output:
  html_document: default
  word_document: default
---

#Libraries required 
```{r}
# install.packages("tidyverse")
# install.packages("dplyr")
# install.packages("purrr")
library(readr)
library(dplyr)
library(tidyverse)
library(ggplot2)
library(purrr)
```


### Read in file.
```{r}
DDSAnalytics  = read.csv("C:/Users/ouska/Desktop/SMU/DOING DS/CaseStudy2_2_2_2_2_2_2/CaseStudy2-data.csv",header = TRUE)
head(DDSAnalytics)
```
