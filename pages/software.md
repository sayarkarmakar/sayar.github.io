---
layout: page
title: softwares
description: Kushal K  Dey's software
---

The following is a list of softwares I have developed over the recent years-

### <a name="CountClust"></a>[CountClust](https://github.com/kkdey/CountClust)

**Version**: 0.0.1
**License**: GPL (>=2)

An [R](http://www.r-project.org/) package to perform, visualize and annotate clustering of counts data using graded membership model.

Check the [Github page](https://github.com/kkdey/CountClust) for codes, description and related documentation.

For vignettes on implementation of this software, check [CountClust vignette](http://rpubs.com/kkdey/128757)


### <a name="tmcmcR"></a>[tmcmcR](https://github.com/kkdey/tmcmcR)

**Version**: 0.1.2
**License**: GPL (>=2)

An [R/C++](https://cran.r-project.org/web/packages/Rcpp/index.html) package to perform transformation based Markov Chain Monte Carlo (TMCMC) approaches. Besides TMCMC and standard RWMH, it also has implementations of various adaptive versions of TMCMC and RWMH (SCAM, RAMA and Atchade's methods) and Metropolis coupling versions (fixed and randomized update).

Check the [Github page](https://github.com/kkdey/tmcmcR) for codes, description and related documentation.

Check the [README](https://github.com/kkdey/tmcmcR/blob/master/README.md) for package description and 
functions.

For vignettes on implementation of this software, check [tmcmcR vignette](https://rpubs.com/kkdey/132076)

For introduction to the methods and materials of TMCMC, along with results on ergodicity and optimal scaling properties,
check [Dey and Bhattacharya 2014](http://arxiv.org/pdf/1408.6667v1.pdf), [Dey and Bhattacharya 2015](http://imstat.org/bjps/papers/BJPS295.pdf), [Dey and Bhattacharya](http://arxiv.org/pdf/1307.1446v4.pdf) and [Dutta and Bhattacharya 2014](http://arxiv.org/abs/1106.5850).

### <a name="cellcycleR"></a>[cellcycleR](https://github.com/kkdey/cellcycleR)

**Version**: 0.0.1
**License**: GPL (>=2)


An [R](http://www.r-project.org/) package to perform re-ordering of single cells on the cell cycle based on sinusoidal cell-cycle gene patterns, tested both for synchronized and unsynchronized single cell experiments.

For vignette and example use  of *cellcycleR*, check the [README](https://github.com/kkdey/cellcycleR/blob/master/README.md).

For various single cell applications of **cellcycleR**, check *cellcyleR applications* [here](http://jhsiao999.github.io/singleCell-method/).

### <a name="ash-cor"></a>[ash-cor](https://github.com/kkdey/ash_stan/utilities)

An [R](http://www.r-project.org/) pipeline for performing adaptive shrinkage on correlation matrix using [ash](https://github.com/stephens999/ashr/) due to Matthew Stephens. Check the R package **ashr** for documentation and details on how to use the adaptive shrinkage method.

Our approach builds on the **ashr** approach and shrinks a correlation matrix. Check the

* [source script](https://github.com/kkdey/ash_stan/blob/master/utilities/ash_cor.R)
* [example use](https://github.com/kkdey/ash_stan/blob/master/utilities/example_ash_cor.R)
* [READ ME](https://github.com/kkdey/ash_stan/blob/master/utilities/ash_cor_README)


