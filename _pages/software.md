---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

We developed the R package <strong>moveHMM</strong> for the analysis of movement data with hidden Markov models. 
<ul>
	<li> <a href="https://cran.r-project.org/package=moveHMM">CRAN</a>: description, documentation, archives... </li>
	<li> <a href="https://github.com/TheoMichelot/moveHMM">Github</a>: latest (unstable) version of the code. </li>
	<li>Get started with <a href="https://cran.r-project.org/web/packages/moveHMM/vignettes/moveHMM-guide.pdf">the vignette</a>. There, we describe the functionalities of the package in detail, and illustrate their use on elk tracking data.</li>
	<li>Short <a href="https://www.youtube.com/watch?v=90LqSNITrN0">video presentation</a> for MEE.</li>
</ul>
<br/>
              
The R package <strong>momentuHMM</strong> extends moveHMM to more general and flexible models. Additional features include: unlimited number of data streams, inclusion of covariates on the observation distribution parameters, centres of attraction, multiple imputation to account for irregular sampling and/or measurement error, etc.<br/>
<ul>
	<li> On <a href="https://cran.r-project.org/package=momentuHMM">CRAN</a>.
	<li> On <a href="https://github.com/bmcclintock/momentuHMM">Github</a>.
	<li> Get started with <a href="https://cran.r-project.org/web/packages/momentuHMM/vignettes/momentuHMM.pdf">the vignette</a>.
</ul>
<br/>

Vianey Leos-Barajas and I wrote <a href="https://arxiv.org/pdf/1806.10639.pdf">a tutorial about using Stan to implement hidden Markov models</a>, in particular to analyse animal movement data. In that document, we re-analyse the wild haggis data set from the moveHMM paper. <br/>
<br/>
		
A while ago, I also wrote <a href="http://media.wix.com/ugd/3708a3_a0a0401708844718a538c2d7c3124224.pdf">a document about implementing hidden Markov models</a> in R and/or C++ (using Rcpp). It describes two examples in detail: a 2-state HMM with Poisson-distributed observations, and a 3-state HMM inspired by movement models. R code is provided for simulation, estimation, and inference in these models.
