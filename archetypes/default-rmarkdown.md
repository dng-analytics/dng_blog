---
title: ''
summary: ''
date: {{ .Date }}
author: []
image:
  preview_only: true
categories: []
tags: []
---


```{r setup, include = FALSE}
pacman::p_load(tidyverse, janitor, here, glue)
knitr::opts_chunk$set(
  collapse = TRUE, comment = "#>", 
  fig.width = 7, 
  fig.align = 'center',
  fig.asp = 0.618, # 1 / phi
  out.width = "700px"
)
```