---
title: "A negative binomial latent factor model for paired microbiome sequencing data"
collection: publications
category: manuscripts
permalink: /publication/01_NBLFM
excerpt: ''
venue: ''
paperurl: 'http://academicpages.github.io/files/NBLFM.pdf'
citation: ''
status: 'WIP'
---

Motivation: Microbiome compositional data are often collected from several body sites and exhibit dependency among them. Analyzing microbial compositions from different sites jointly allows for effective borrowing of information by exploiting the underlying cross-site correlation, which can lead to more effective statistical analysis, especially when the sample size at one or both sites is limited. To this end, we introduce a joint model for microbiome compositions at two (or more) sites within the same subjects. Our model incorporates (i) latent factors shared across two body sites to explain the common subject effects and to serve as the source of correlation between the two sites; and (ii) mixtures of latent factors to allow heterogeneity among the subjects in their level of cross-site association. The model is illustrated with synthetic data and we apply it in a case study involving samples of the urinary and vaginal microbiome collected from women.

Results: Simulation studies show how common subject effects influence regression analysis results; a stronger association between two sites in the data causes a greater degree of bias in the analysis. The model with latent factors mitigates the bias present in the model without latent factors, whereas the two models perform comparably for the data set without paired associations. In a case study involving samples collected from a study on the female urogenital microbiome with aging, our model leads to the detection of covariate associations of the vaginal and urinary microbiome composition that are otherwise not statistically significant under a similar regression model applied to the two sites separately. Our model also enables prediction of the microbial abundance at one site based on observations from another, improving predictive power. We consider a model extension that allows the clustering of subjects (samples) and cluster-specific levels of paired association. Under the extended modeling framework, the clusters can be classified according to their association strengths.
