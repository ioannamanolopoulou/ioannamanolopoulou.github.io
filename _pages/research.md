---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My main research interest is in developing, extending or re-evaluating Bayesian models with a view to producing inferences which are useful and interpretable in practical applications. My focus is in flexible modelling tools such as mixture models and tree models. For a complete list of publications (which is most up-to-date) visit my [google scholar profile](https://scholar.google.com/citations?user=QkdqkzYAAAAJ&hl=en). 


## Causal inference for heterogeneous treatment effects

I am interested in the use of flexible tree models to infer heterogeneous treatment effects through non-parametric regression modelling. Hahn et al recently developed Bayesian Causal Forests (BCF) using a natural parameterisation that allows us to place priors (and therefore smoothing) directly on treatment effects.
In our recent work we developed an extension to BCF to apply targeted shrinkage across the different covariates. 

Different aspects of this work were jointly developed with my PhD students [Alberto Caron](https://albicaron.github.io/) and Ilina Yozova as well as collaborators [Gianluca Baio](http://www.statistica.it/gianluca/) and [Richard Hahn](https://math.asu.edu/node/2746). 

* A. Caron, G. Baio and I. Manolopoulou, [Sparse Bayesian Causal Forests for Heterogeneous Treatment Effect Estimation.](https://arxiv.org/abs/2102.06573)
* A. Caron, G. Baio and I. Manolopoulou, [Estimating Individual Treatment Effects using Non-Parametric Regression Models: a Review](https://arxiv.org/abs/2009.06472)
* A. Caron, G. Baio and I. Manolopoulou, [ Counterfactual Learning with Multioutput Deep Kernels](https://openreview.net/pdf?id=iGREAJdULX)
* A. Caron, G. Baio and I. Manolopoulou, []()

## Interpretability and coherence of topic models

Topic models (and mixture models in general) are powerful tools in non-parametric estimation. However, quantities such as posterior mean and uncertainty are generally not interpretable for mixture models, because of their inherent label uncertainty. I am interested in producing meaningful summaries of posterior distributions over mixture models, and using these to construct further model pieces. 

This is joint work with my former PhD student Mariflor Vega-Carrasco and collaborators 
[Mirco Musolesi](https://www.mircomusolesi.org/), [Rosie Prior](https://www.linkedin.com/in/rosie-prior-96275024/) and [Jason O'Sullivan](https://www.linkedin.com/in/jason-o-sullivan/?originalSubdomain=uk) as part of our collaboration with [dunnhumby ltd](https://www.dunnhumby.com/) 

* M. Vega Carrasco, J. O'Sullivan, R. Prior, I. Manolopoulou and M. Musolesi, 
[Posterior Summaries of Grocery Retail Topic Models: Evaluation, Interpretability and Credibility.](https://academic.oup.com/jrsssc/article/71/3/562/7067601)
* M. Vega Carrasco, M. Musolesi, J. O'Sullivan, R. Prior and I. Manolopoulou, 
[Regional Shopping Objectives in British Grocery Retail Transactions Using Segmented Topic Models](https://onlinelibrary.wiley.com/doi/full/10.1002/asmb.2890). 


## Applications of Bayesian non-parametric modelling to rater heterogeneity

Bayesian non-parametric and semi-parametric models are a flexible way of capturing heterogeneity in complex data. 
Rater heterogeneity, where different raters provide scores for different subjects, are a natural application
of such models. This is joint work with my visiting PhD student, [Giuseppe Mignemi](https://scholar.google.com/citations?user=yvfdM3cAAAAJ&hl=en). 

* Giuseppe Mignemi, Ioanna Manolopoulou [Bayesian Nonparametric Models for Multiple Raters: a General Statistical Framework](https://arxiv.org/abs/2410.21498). Submitted.

* Giuseppe Mignemi, Antonio Calcagnì and Andrea Spoto 
[Mixture polarization in inter‑rater agreement analysis: a Bayesian nonparametric index](https://link.springer.com/article/10.1007/s10260-023-00741-x) 




## Bayesian modelling in partially identified models

Although there is currently an abundance of data available through a variety of sources, much of these datasets are collected through unknown (and biased) sampling processes. This naturally leads to an identifiability problem in terms of any downstream modelling: if we don't know exactly how the data were collected, and we don't know who's missing from the dataset, what can we say about the population? No amount of data can fix this problem, instead careful consideration of the underlying data generative process and unknown sampling mechanism is needed. 

This is joint work with my former PhD student [Helen (Zhenzheng) Hu](https://www.turing.ac.uk/people/doctoral-students/zhenzheng-helen-hu) and collaborators [Ioannis Kosmidis](http://www.ikosmidis.com/), [Richard Hahn](https://math.asu.edu/node/2746), [Jared Murray](https://jaredsmurray.github.io/). 

* H. Hu, I. Kosmidis and I. Manolopoulou, Misclassification in binary regression modelling (in preparation). 
* R. Hahn, J. Murray and I. Manolopoulou, [A Bayesian partial identification approach to inferring the prevalence of accounting misconduct.](https://arxiv.org/abs/1407.8430)



## Bayesian modelling in health economics

Quantifying the impact of uncertainty on decisions is an important aspect of health-economic decision making. The analysis of the Value of Information (VoI) is an increasingly popular method for quantifying decision uncertainty, but it is frequently computationally prohibitive. This work used ideas from non-parametric modelling and moment-matching to allow feasible calculation of VoI summaries such as Expected Value of Partial Perfect Information (EVPPI) and the Expected Value of Sample Information (EVSI).

This is joint work with my former PhD student [Anna Heath](https://sites.google.com/site/annaheathstats/) and collaborator [Gianluca Baio](http://www.statistica.it/gianluca/). 

* A. Heath, I. Manolopoulou and G. Baio, [Estimating the Expected Value of Partial Perfect Information in Health Economic Evaluations using Integrated Nested Laplace Approximation.](https://arxiv.org/abs/1504.05436)
* A. Heath, I. Manolopoulou and G. Baio, [A Review of Methods for the Analysis of the Expected Value of Information.](https://arxiv.org/abs/1507.02513)
* A. Heath, I. Manolopoulou and G. Baio, [Estimating the Expected Value of Sample Information across Different Sample Sizes using Moment Matching and Non-Linear Regression.](https://arxiv.org/abs/1804.09590)


## Bayesian modelling in retail analytics
I've had a long-standing collaboration with [dunnhumby ltd](https://www.dunnhumby.com/) where our first few projects focused on developing models for the sales of slow-moving goods using Bayesian hierarchical self-exciting processes, as well as characterising differences in the competitive behaviour of different product groups. 


This was joint work with my former PhD student [James Pitkin](https://www.linkedin.com/in/james-pitkin-49693a33/?originalSubdomain=uk) and collaborators [Gordon Ross](https://www.maths.ed.ac.uk/school-of-mathematics/people/a-z?person=593),  [Rosie Prior](https://www.linkedin.com/in/rosie-prior-96275024/) and [Jason O'Sullivan](https://www.linkedin.com/in/jason-o-sullivan/?originalSubdomain=uk). 


* J. Pitkin, G. Ross and I. Manolopoulou, [Dirichlet Process Mixtures of Order Statistics with Applications to Retail Analytics](https://arxiv.org/abs/1805.05671).
* J. Pitkin, I. Manolopoulou and G. Ross, [Bayesian hierarchical modelling of sparse count processes in retail analytics](https://arxiv.org/abs/1805.05657).

## Diffusion modelling 

I have used diffusion models to describe trajectories of various organisms. This work was motivated by immune cell data collected by 2-photon microscopy from inside the lymphnode of a live mouse, but was later extended to capture patterns of animal movement using Bayesian non-parametric diffusion models. 


This was joint work with [Mike West](https://www2.stat.duke.edu/~mw/), [Melanie Matheu](https://www.linkedin.com/in/melaniematheu/) and [Mike Cahalan](http://www.immunology.uci.edu/profiles/cahalan-michael.asp), and more recently  with [Yvo Pokern](https://www.ucl.ac.uk/statistics/people/yvopokern) and [Tjun-Yee Hoh](https://people.maths.bris.ac.uk/~ea19261/index.html).


* I. Manolopoulou, M. P. Matheu, M. D. Cahalan, M. West and T. B. Kepler, [Bayesian Spatio-Dynamic Modeling in Cell Motility Studies: Learning Nonlinear Taxic Fields Guiding the Immune Response](https://www.tandfonline.com/doi/full/10.1080/01621459.2012.655995)
