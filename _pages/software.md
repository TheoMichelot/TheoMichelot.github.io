---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

# moveHMM

We developed the R package **moveHMM** for the analysis of movement data with hidden Markov models. 

	- [CRAN](https://cran.r-project.org/package=moveHMM): description, documentation, archives...
	
	- [Github](https://github.com/TheoMichelot/moveHMM): latest (unstable) version of the code.
	
	- Get started with [the vignette](https://cran.r-project.org/web/packages/moveHMM/vignettes/moveHMM-guide.pdf. There, we describe the functionalities of the package in detail, and illustrate their use on elk tracking data.
	
	- Short [video presentation](https://www.youtube.com/watch?v=90LqSNITrN0) for MEE.
         
# momentuHMM

The R package **momentuHMM** extends moveHMM to more general and flexible models. Additional features include: unlimited number of data streams, inclusion of covariates on the observation distribution parameters, centres of attraction, multiple imputation to account for irregular sampling and/or measurement error, etc.

	- On [CRAN](https://cran.r-project.org/package=momentuHMM).
	
	- On [Github](https://github.com/bmcclintock/momentuHMM).
	
	- Get started with [the vignette](https://cran.r-project.org/web/packages/momentuHMM/vignettes/momentuHMM.pdf).

# Other R packages

	- [**smoothSDE**](https://github.com/TheoMichelot/smoothSDE) can be used to fit varying-coefficient stochastic differential equations, described in this paper.

	- [**MScrawl**](https://github.com/TheoMichelot/MScrawl) is a package to fit state-switching continuous-time correlated random walks using MCMC, as described in this paper.
	
	- [**localGibbs**](https://github.com/TheoMichelot/localGibbs) implements the local Gibbs model for animal movement and habitat selection, presented in this paper and this paper.

# Miscellaneous

Vianey Leos Barajas and I wrote [a tutorial about using Stan to implement hidden Markov models](https://arxiv.org/pdf/1806.10639.pdf), in particular to analyse animal movement data. In that document, we re-analyse the wild haggis data set from the moveHMM paper.
		
A while ago, I also wrote [a document about implementing hidden Markov models](http://media.wix.com/ugd/3708a3_a0a0401708844718a538c2d7c3124224.pdf) in R and/or C++ (using Rcpp). It describes two examples in detail: a 2-state HMM with Poisson-distributed observations, and a 3-state HMM inspired by movement models. R code is provided for simulation, estimation, and inference in these models.
