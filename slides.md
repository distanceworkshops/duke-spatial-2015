---
title: Lecture slides
layout: index

---

# Slides

Here you can find the slides used in the lectures. They are provided in three formats: PDF (for printing), HTML (for viewing online, with animations) and the source R presentation files (so you can see how all the graphics were produced).

## Classroom

Lecture name                                |     PDF                                  |                      HTML               |             Rpres
--------------------------------------------|------------------------------------------|-----------------------------------------|-----------------------------------------------
Welcome                                     | [PDF](slides/1-welcome-landscape.pdf)    | [HTML](slides/1-welcome-landscape.html) | [Rpres](/slides/1-welcome-landscape.Rpres)
Introduction to distance sampling           | [PDF](slides/2-intro-ds.pdf)             | [HTML](slides/2-intro-ds.html)          | [Rpres](/slides/2-intro-ds.Rpres)
Advanced distance sampling                  | [PDF](slides/3-adv-ds.pdf)               | [HTML](slides/3-adv-ds.html)            | [Rpres](/slides/3-adv-ds.Rpres)
What is a density surface model?            | [PDF](slides/4-what-is-a-dsm.pdf)        | [HTML](slides/4-what-is-a-dsm.html)     | [Rpres](/slides/4-what-is-a-dsm.Rpres)
Generalized Additive Models                 | [PDF](slides/5-gams.pdf)                 | [HTML](slides/5-gams.html)              | [Rpres](/slides/5-gams.Rpres)
Adding covariates to density surface models | [PDF](slides/6-covariates.pdf)           | (none)                                  | (none)
Multivariate smoothing, model selection     | [PDF](slides/7-multiple-smooths.pdf)     | [HTML](slides/7-multiple-smooths.html)  | [Rpres](/slides/7-multiple-smooths.Rpres)
Making predictions                          | [PDF](slides/8-prediction.pdf)           | [HTML](slides/8-prediction.html)        | [Rpres](/slides/8-prediction.Rpres)
Estimating variance                         | [PDF](slides/9-variance.pdf)             | [HTML](slides/9-variance.html)          | [Rpres](/slides/9-variance.Rpres)
Practical advice                            | [PDF](slides/xx-practical-advice.pdf)    | [HTML](slides/xx-practical-advice.html) | [Rpres](/slides/xx-practical-advice.Rpres)
Advanced topics                             | [PDF](slides/xx-advanced-topics.pdf)     | [HTML](slides/xx-advanced-topics.html)  | [Rpres](hslides/xx-advanced-topics.Rpres)
Extrapolating (Laura Mannocci)              | [PDF](slides/extrapolation-mannocci.pdf) |  (none)                                 | (none)

## Lab

Lecture name                             |                      PDF          |   HTML       |  Rpres
-----------------------------------------|-----------------------------------|--------------|---------
Software setup                           | [PDF](slides/Software_Setup.pdf)  | (none)       | (none)
Lab 1                                    | [PDF](slides/Lab_1.pdf)           | (none)       | (none)

## Building the slides yourself

You'll need some extra R packages to get the code in the presentations to run. Issuing the following command should ensure that they work.

```{r}
install.packages(c("Distance", "RColorBrewer", "animation", "dsm", "ggplot2",
                   "gridExtra", "knitr", "magrittr", "mgcv", "numDeriv",
                   "plyr", "raster", "reshape2", "rgdal", "statmod", "tweedie",
                   "viridis", "htmltools", "caTools", "bitops", "rmarkdown",
                   "tweedie"))
```
Data used in the slides is in the `spermwhale-analysis` directory of [this github repository](https://github.com/DistanceDevelopment/spatial-workshops/tree/97a1f6fcf01ee7177f23720ae322350bd180a6aa). It may well be easier to download all files in the repository (use the "Download ZIP" button in the right hand side) if you wish to rebuild the slides from scratch (using RStudio).

