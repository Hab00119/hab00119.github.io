---
title: "Automated spectral preprocessing via Bayesian optimization for chemometric analysis of milk constituents"
authors:
- me
- Owen M McDougal
- Timothy Andersen
date: "2025-08-27T00:00:00Z"
publishDate: "2025-08-27T00:00:00Z"

publication_types: ["article-journal"]

publication: "*Foods, 14*(17)"
publication_short: "Foods"

abstract: The preprocessing of infrared spectra can significantly improve predictive accuracy for protein, carbohydrate, lipid, or other nutrition components, yet optimal preprocessing selection is typically empirical, tedious, and dataset specific. This study introduces a Bayesian optimization-based framework designed for the automated selection of optimal spectral preprocessing pipelines within a chemometric modeling context. The framework was applied to mid-infrared spectra of milk to predict compositional parameters for fat, protein, lactose, and total solids. A total of 385 averaged spectra corresponding to 198 unique samples was split into a 70/30 ratio (training/test) using a group-aware Kennard-Stone algorithm, resulting in 269 averaged spectra (135 unique samples) for training and 116 spectra (58 unique samples) for testing. Six regression models (Elastic Net, Gradient Boosting Machines, Partial Least Squares, RidgeCV Regression, LassoLarsCV, and Support Vector Regression) were evaluated across three preprocessing conditions. Optimized preprocessing consistently outperformed other methods, with RidgeCV achieving the best performance for all components except lactose, where PLS slightly outperformed it. The best RMSEP results were achieved for protein (RMSEP = 0.054, R² = 0.981) and lactose (RMSEP = 0.026, R² = 0.917), followed by fat (RMSEP = 0.139, R² = 0.926) and total solids (RMSEP = 0.154, R² = 0.960). By eliminating manual trial and error, this data-driven strategy offers a robust and generalizable solution that streamlines spectral modeling in dairy analysis and can be readily applied to other types of spectroscopic data across various domains.

summary: Bayesian optimization framework for automated selection of optimal spectral preprocessing pipelines in chemometric analysis of milk constituents, achieving R² > 0.91 for all components.

tags:
- Bayesian Optimization
- Chemometrics
- Machine Learning
- Spectroscopy
- Dairy Science
- Automated Pipeline
featured: true

links:
  - type: pdf
    url: https://www.mdpi.com/2304-8158/14/17/2996/pdf
  - type: source
    url: https://www.mdpi.com/2304-8158/14/17/2996

hugoblox:
  ids:
    doi: 10.3390/foods14172996
---
