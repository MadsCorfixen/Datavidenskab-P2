---
title: "Simulering af Data"
author: "Mads"
date: "06/02/2020"
output:
  pdf_document: default
  html_document: default
---

Her er noget tekst

```r
sim_data_normal = rnorm(n = 1000, mean = 0, sd = 1)
hist(sim_data_normal)
```

![](Simluering_af_data_files/figure-latex/unnamed-chunk-1-1.pdf)<!-- --> 


```r
sim_data_unif = runif(n = 1000, min = 0, max = 10)
hist(sim_data_unif)
```

![](Simluering_af_data_files/figure-latex/unnamed-chunk-2-1.pdf)<!-- --> 


```r
sim_data_binom = rbinom(n = 1000, size = 20, prob = 0.5)
hist(sim_data_binom)
```

![](Simluering_af_data_files/figure-latex/unnamed-chunk-3-1.pdf)<!-- --> 

