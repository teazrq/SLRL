--- 
title: "Statistical Learning and Machine Learning with R"
author: "[Ruoqing Zhu](https://sites.google.com/site/teazrq/)"
date: "2021-06-23"
github-repo: teazrq/SMLR
url: 'https://teazrq.github.io/SMLR/'
knit: "bookdown::render_book"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib]
biblio-style: apalike
favicon: "favicon.ico"
link-citations: yes
urlcolor: cyan
description: ""
---



# Preface {-}

Welcome to *Statistical Learning and Machine Learning with R*! I started this project during the summer of 2018 when I was preparing for the Stat 432 course. At that time, our faculty member [Dr. David Dalpiaz](https://daviddalpiaz.com/teaching.html), had decided to move to The Ohio State University (although he later on moved back to UIUC). David introduced to me this awesome way of publishing website on GitHub, which is a very efficient approach for developing courses. Since I was also teaching Stat 542 (Statistical Learning) for several years, I figured it could be beneficial to integrate what I have to this [existing book](https://daviddalpiaz.github.io/r4sl/) by David and use it as the R material for both courses. For Stat 542, the main focus is to learn the numerical optimization behind these learning algorithms, and also be familiar with the theoretical background. As you can tell, I am not being very creative on the name, so `SMLR' it is. You can find the source file of this book on my [GitHub](https://teazrq.github.io/SMLR/).

## Target Audience {-}

This book can be suitable for students ranging from advanced undergraduate to first/second year Ph.D students who have prior knowledge in statistics. Although a student at the masters level will likely benefit most from the material. Previous experience with both basic mathematics (mainly linear algebra), statistical modeling (such as linear regressions) and R are assumed.

## What's Covered? {-}

I currently plan to include the following topics:

1. Basic Knowledge in R
2. Linear and Penalized Linear Models
3. Numerical Optimization Basics
4. Classification
5. Non-parametric Statistical Models
6. Machine Learning Models
7. Unsupervised Learning
8. Appendix

The goal of this book is to introduce not only how to run some of the popular statistical learning models in R, but also know the algorithms and programming techniques for solving these models. For each section, the difficulty will gradually increase from an undergraduate level to a graduate level. 

It will be served as a supplement to [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) [@james2013introduction] for [STAT 432 - Basics of Statistical Learning](https://go.illinois.edu/stat432) and [The Elements of 
Statistical Learning: Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/) [@hastie2001elements] for [STAT 542 - Statistical Learning](https://go.illinois.edu/stat542) at the [University of Illinois at Urbana-Champaign](http://illinois.edu/).

**This book is under active development**. Hence, you may encounter errors ranging from typos to broken code, to poorly explained topics. If you do, please let me know! Simply send an email and I will make the changes as soon as possible (`rqzhu AT illinois DOT edu`). Or, if you know `R Markdown` and are familiar with GitHub, [make a pull request and fix an issue yourself!](https://github.com/teazrq/SLWR). These contributions will be acknowledged. 

## Acknowledgements {-}

The initial contents are derived from Dr. David Dalpiaz's book. My STAT 542 course materials are also inspired by Dr. Feng Liang and Dr. John Marden who developed earlier versions of this course. And I also incorporated many online resources, such as 

- [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
- [R Programming for Data Science](http://r4ds.had.co.nz/)
and others through Google search.

## License {-}

![This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).](images/cc.png)
