---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

My research focuses on developing, extending or re-evaluating Bayesian models with a view to producing inferences which are useful and interpretable in practical applications. My main focus is in flexible modelling tools such as mixture models and tree models. 


## Causal inference for heterogeneous treatment effects

I am interested in the use of flexible tree models to infer heterogeneous treatment effects through non-parametric regression modelling. Hahn et al recently developed Bayesian Causal Forests (BCF) using a natural parameterisation that allows us to place priors (and therefore smoothing) directly on treatment effects.
In our recent work we developed an extension to BCF to apply targeted shrinkage across the different covariates. 

This is joint work with my PhD students Alberto Caron and Ilina Yozova as well as collaborators Gianluca Baio and Richard Hahn. 


## Interpretability and coherence of topic models

Topic models (and mixture models in general) are powerful tools in non-parametric estimation. However, quantities such as posterior mean and uncertainty are generally not interpretable for mixture models, because of their inherent label uncertainty. I am interested in producing meaningful summaries of posterior distributions over mixture models, and using these to construct further model pieces. 

This is joint work with my former PhD student Mariflor Vega and collaborators Mirco Musolesi, Rosie Prior and Jason O'Sullivan. 


## Bayesian modelling in partially identified models

Although there is currently an abundance of data available through a variety of sources, much of these datasets are collected through unknown (and biased) sampling processes. This naturally leads to an identifiability problem in terms of any downstream modelling: if we don't know exactly how the data were collected, and we don't know who's missing from the dataset, what can we say about the population? No amount of data can fix this problem, instead careful consideration of the underlying data generative process and unknown sampling mechanism is needed. 

This is joint work with my former PhD student Helen (Zhenzheng) Hu and collaborators Ioannis Kosmidis, Richard Hahn, Jared Murray. 


## Bayesian modelling in health economics

This is joint work with my former PhD student Anna Heath and collaborator Gianluca Baio. 


## Diffusion modelling 

