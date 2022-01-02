---
author: Yuan Ge; Wenchao Ma; Kaiwen Man
categories:

date: "2021-12-31"
draft: false
excerpt: This theme has a form-to-email feature built in, thanks to the simple Formspree
  integration. All you need to activate the form is a valid recipient email address
  saved in the form front matter.
layout: single

subtitle: Model Development, Q-matrix Validation and Model Comparison
tags:
title: A Sequential Cognitive Diagnosis Model For Graded Response 
---

---
### Abstract

Cognitive diagnosis models (CDMs) refer to a set of psychometric models that intend to group individuals into latent classes with distinct skill profiles. A number of CDMs have been proposed; Regardless of their parametrizations, most CDMs rely on a Q-matrix (Tatsuoka, 1983), which specifies whether an attribute is measured by an item. The importance of the Q-matrix in CDM analyses cannot be overemphasized. It has been widely recognized that a misspecified Q-matrix can degrade item parameter estimation, produce poor model-data fit, and result in erroneous attribute estimation.
In order to correct the potential misspecifications, several empirical Q-matrix validation methods have been proposed. Among them, the stepwise Wald procedure (Ma & de la Torre, 2020), which incorporates a formal hypothesis test with an effect size measure, has been shown to perform well in general. A major limitation of this procedure is that, although the Q-matrix is very likely to be misspecified, the variance-covariance matrix used for the Wald test was estimated using the outer-product-of-gradient method, which is known to be less accurate when the model is not correctly specified. The primary goal of this study is to assess the performance of the stepwise Wald procedure with a robust variance-covariance estimator under varied simulation conditions. This study manipulates sample size, test length, the proportion of misspecifications in the Q-matrix, and skill distributions. This study also assesses how the identifiability of the Q-matrix affects the performance of the stepwise Wald method. For comparison, other Q-matrix validation procedures will also be compared.
