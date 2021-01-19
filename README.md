# Easy-MLE

This repository provides resources for handful of models for maximum likelihood estimation (MLE). I find that most resources for MLE in R are either: 1) unclear, esoteric, and difficult to implement, or 2) baked into packages which are prone to bugs and lack useful transparency to the underlying math. My goal is to provide a streamlined way to estimate these models, while making transparent and digestible the math that powers them.

I cover models for: bivariate outcomes (logit), ordinal outcomes (ordered logit, ordered probit), multinomial outcomes (multinomial logit), and count outcomes (poisson, negative binomial). The resources for each topic are organized as follows:

  1. Brief overview of the model and use cases
  2. Pre-written functions to prepare data and estimate models, with in-line documentation
  3. Example code with data from my own work

The only packages you'll need for this repository are `tidyverse` and `MASS`.

I occasionally make references to two textbooks:
  1. Long (1997) - Regression Models for Categorical and Limited Dependent Variables (This book is AWESOME, I highly recommend getting a copy if you are at all interested in MLE)
  2. Ward and Ahlquist (2018) - Maximum Likelihood for Social Science
