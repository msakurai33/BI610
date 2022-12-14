---
layout: page
title: Course schedule, 2020/2021
description: schedule, with links to slides and homeworks
---

The (Rmarkdown) source code for these lectures is available at [the github repository](https://github.com/UO-Biostats/UO_ABS),
or by replacing the `.slides.html` suffix with `.Rmd` in the link below;
the slides are made using [reveal.js](https://github.com/hakimel/reveal.js/).

Below:
- [Fall 2020](#fall-2020)
- [Winter 2021](#winter-2021)


# Fall 2020

Week 1 (*9/29*)

: Overview of data science - description and estimation, uncertainty and simulation,
    with examples for comparing means and linear regression; smoothing.

    - [Slides](../CLASS_MATERIALS/Lectures/2020/Week_01_Lecture.slides.html)
    - topic slides: [the t distribution](../CLASS_MATERIALS/Lectures/2020/t-distribution.slides.html)
    - topic slides: [the central limit theorem and the Normal distribution](../CLASS_MATERIALS/Lectures/2020/central-limit-theorem.slides.html)
    - [Homework 1](../CLASS_MATERIALS/Homeworks/F20W21/HW01_F20.html) *(due 10/8)*
    - [how to git the slide source](using-git.html)
    - Reading: Quinn & Keough chapters 1-4

Week 2 (*10/6*)

: Analysis of Variance (ANOVA) and experimental design; tidy data; power and false positives

    - slides: [confidence intervals](../CLASS_MATERIALS/Lectures/2020/Week_02_Confidence_Intervals.slides.html)
    - slides: [ANOVA](../CLASS_MATERIALS/Lectures/2020/Week_02_ANOVA.slides.html)
    - slides: [experimental design](../CLASS_MATERIALS/Lectures/2020/Week_02_Experimental_design.slides.html)
    - [Homework 2](../CLASS_MATERIALS/Homeworks/F20W21/HW02_F20.html) *(due 10/15)*
    - Reading: Quinn & Keough chapters 5, 7, 8

Week 3 (*10/13*)

: Plotting/visualization, and permutation/bootstrapping

    - slides: [permutation tests](../CLASS_MATERIALS/Lectures/2020/Week_03_Permutation_tests.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_03_Permutation_tests.handout.pdf)
    - slides: [tidy data](../CLASS_MATERIALS/Lectures/2020/Week_03_Tidy_data.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_03_Tidy_data.handout.pdf)
    - slides: [visualizing data](../CLASS_MATERIALS/Lectures/2020/Week_03_Visualization.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_03_Visualization.handout.pdf)
    - slides: [the bootstrap](../CLASS_MATERIALS/Lectures/2020/Week_03_Bootstrap.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_03_Bootstrap.handout.pdf)
    - [Homework 3](../CLASS_MATERIALS/Homeworks/F20W21/HW03_F20.html) *(due 10/22)*
    - Reading: Quinn & Keough chapter 9

Week 4 (*10/20*)

: Multivariate ANOVA, regression, least-squares likelihood

    - slides: [multivariate ANOVA](../CLASS_MATERIALS/Lectures/2020/Week_04_Multivariate_ANOVA.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_04_Multivariate_ANOVA.handout.pdf)
    - slides: [formulas](../CLASS_MATERIALS/Lectures/2020/Week_04_Formulas.slides.html)
        and [pdf version](../CLASS_MATERIALS/Lectures/2020/Week_04_Formulas.handout.pdf)
    - [Homework 4](../CLASS_MATERIALS/Homeworks/F20W21/HW04_F20.html) *(due 10/30)*
    - Reading: Quinn & Keough chapter 6

Week 5 (*10/27*)

: Model selection; random effects and mixed models - a first look.

    - slides: [Linear models](../CLASS_MATERIALS/Lectures/2020/Week_05_Linear_models.slides.html)
    - slides: [Model comparison](../CLASS_MATERIALS/Lectures/2020/Week_05_Model_comparison.slides.html)
    - slides: [Random effects](../CLASS_MATERIALS/Lectures/2020/Week_05_Random_effects.slides.html)
    - Homework: [peer review](peer_reviews.html)
    - Reading: Quinn & Keough chapter 13

Week 6 (*11/3*)

: Multiple testing, error rates, and some history.

    - slides: [Multiple testing](../CLASS_MATERIALS/Lectures/2020/Week_06_Multiple_testing.slides.html)
    - slides: [Statistics and Eugenics](../CLASS_MATERIALS/Lectures/2020/Week_06_Statistics_and_eugenics.slides.html)
    - install [Stan](https://mc-stan.org)
    - [Homework 6](../CLASS_MATERIALS/Homeworks/F20W21/HW06_F20.html) *(due 11/12)*

Week 7 (*11/10*)

: Introduction to Bayesian statistics

    - slides: [Prior distributions and uncertainty](../CLASS_MATERIALS/Lectures/2020/Week_07_Prior_distributions.slides.html)
    - slides: [Probability rules](../CLASS_MATERIALS/Lectures/2020/Week_07_Probability_rules.slides.html)
    - slides: [the Beta distribution](../CLASS_MATERIALS/Lectures/2020/Week_07_Beta_distribution.slides.html)
    - slides: [Sampling from the posterior with Markov chain Monte Carlo](../CLASS_MATERIALS/Lectures/2020/Week_07_Posterior_sampling.slides.html)
    - Reading: Kruschke, chapters 1, 2, 4, 5, 6, 7
    - [Homework 7](../CLASS_MATERIALS/Homeworks/F20W21/HW07_F20.html) *(due 11/19)*

Week 8 (*11/17*)

: Bayesian hierarchical modeling - shrinkage, and sharing power

    - slides: [Hierarchical models: adding levels of randomness](../CLASS_MATERIALS/Lectures/2020/Week_08_Levels_of_randomness.slides.html)
    - slides: [Hierarchical models: Baseball data](../CLASS_MATERIALS/Lectures/2020/Week_08_Baseball.slides.html)
    - Reading: Kruschke, chapters 9, 10
    - [Homework 8](../CLASS_MATERIALS/Homeworks/F20W21/HW08_F20.html) *(due 12/03)*

Week 9 (*11/24*)

: Logistic models, and sharing power

    - slides: [The logistic model](../CLASS_MATERIALS/Lectures/2020/Week_09_Logistic_model.slides.html)
    - slides: [Sharing power and shrinkage](../CLASS_MATERIALS/Lectures/2020/Week_09_Sharing_power.slides.html)
    - slides: [The Gamma and Exponential distributions](../CLASS_MATERIALS/Lectures/2020/Week_09_Gamma_distribution.slides.html)
    - Reading: Kruschke, chapters 13, 21
    - no new homework this week (catch up on reading?)

Week 10 (*12/1*)

: Robust linear models; Generalized Linear Models (GLMs).

    - slides: [Fitting linear models, robustly](../CLASS_MATERIALS/Lectures/2020/Week_10_Robust_fitting.slides.html)
    - slides: [Generalized Linear Models](../CLASS_MATERIALS/Lectures/2020/Week_10_GLMs.slides.html)
    - slides: [Summary and wrap-up](../CLASS_MATERIALS/Lectures/2020/Week_10_Summary.slides.html)
    - slides: [Poisson linear models](../CLASS_MATERIALS/Lectures/2020/Week_10_Poisson_linear_models.slides.html)
    - slides: [The Cauchy distribution](../CLASS_MATERIALS/Lectures/2020/Week_10_Cauchy_distribution.slides.html)
    - slides: [The Poisson distribution](../CLASS_MATERIALS/Lectures/2020/Week_10_Poisson_distribution.slides.html)
    - slides: [Matrix multiplication](../CLASS_MATERIALS/Lectures/2020/Week_10_Matrix_multiplication.slides.html)
    - [Homework 9](../CLASS_MATERIALS/Homeworks/F20W21/HW09_F20.html) *(due 12/10)*
    - Reading: Kruschke, chapters 15, 16, 17

# Winter 2021

Week 11 (*1/4*)

: Survival analysis and [introductiom to `brms`](https://github.com/paul-buerkner/brms)

    - slides: [Survival curves](../CLASS_MATERIALS/Lectures/2020/Week_11_Survival_curves.slides.html)
    - slides: [Cox's Proportional Hazards](../CLASS_MATERIALS/Lectures/2020/Week_11_Cox_proportional_hazards.slides.html)
    - slides: [the Weibull distribution](../CLASS_MATERIALS/Lectures/2020/Week_11_Weibull_distribution.slides.html)
    - slides: [Parametric survival analysis](../CLASS_MATERIALS/Lectures/2020/Week_11_Parametric_survival_analysis.slides.html)
    - slides: [Introduction to brms](../CLASS_MATERIALS/Lectures/2020/Week_11_Intro_to_brms.slides.html)
    - [Homework 11](../CLASS_MATERIALS/Homeworks/F20W21/HW11_W21.html) *(due 1/14)*

Week 12 (*1/11*)

: Time series: temporal autocorrelation, autoregressive models; mechanistic models

    - slides: [Time series](../CLASS_MATERIALS/Lectures/2020/Week_12_Time_series.slides.html)
    - slides: [Missing data and imputation](../CLASS_MATERIALS/Lectures/2020/Week_12_Missing_data.slides.html)
    - slides: [Trends, smoothing, autocorrelation, and cycles](../CLASS_MATERIALS/Lectures/2020/Week_12_Trend_and_cycles.slides.html)
    - [Homework 12](../CLASS_MATERIALS/Homeworks/F20W21/HW12_W21.html) *(due 1/21)*


Week 13 (*1/18*)

: Categorical data: chi-square for contingency tables, permutation tests.

    - slides: [The chi-squared test for categorical data](../CLASS_MATERIALS/Lectures/2020/Week_13_Categorical_chisquared.slides.html)
    - slides: [Permutation testing for categorical data](../CLASS_MATERIALS/Lectures/2020/Week_13_Categorical_permutation.slides.html)
    - slides: [Poisson models for categorical data (using brms)](../CLASS_MATERIALS/Lectures/2020/Week_13_Categorical_brms.slides.html)
    - slides: [The chi-squared distribution](../CLASS_MATERIALS/Lectures/2020/Week_13_Chi_squared.slides.html)
    - [Homework 13](../CLASS_MATERIALS/Homeworks/F20W21/HW13_W21.html) *(group homework, due 1/27)*
    - Reading: Kruschke, chapter 16 (metric data with one or two groups), and
        chapter 24 (Poisson, contingency tables)

Week 14 (*1/25*)

: Crossvalidation for model comparison; sparsifying priors and variable selection

    - slides: [Crossvalidation and overfitting](../CLASS_MATERIALS/Lectures/2020/Week_14_Crossvalidation.slides.html)
    - slides: [Overdispersion](../CLASS_MATERIALS/Lectures/2020/Week_14_Overdispersion.slides.html)
    - slides: [Reparameterization](../CLASS_MATERIALS/Lectures/2020/Week_14_Reparameterization_in_stan.slides.html)
    - slides: [R interlude: indexing](../CLASS_MATERIALS/Lectures/2020/Week_14_Interludes.slides.html)
    - Reading: Kruschke, chapters 17 (one-variable linear models), 18 (multivariate linear models)

Week 15 (*2/1*)

: Many response variables

    - slides: [The multivariate normal distribution](../CLASS_MATERIALS/Lectures/2020/Week_15_Multivariate_normal.slides.html)
    - slides: [Multivariate responses](../CLASS_MATERIALS/Lectures/2020/Week_15_Multivariate_responses.slides.html)
    - [Primer on linear algebra](../CLASS_MATERIALS/Lectures/2019/LA_primer_slides.html)
    - [Rmd file for the primer](../CLASS_MATERIALS/Lectures/2019/LA_primer_slides.Rmd)
    - [Homework 14](../CLASS_MATERIALS/Homeworks/F20W21/HW14_W21.html) *(group homework, due 2/9)*

Week 16 (*2/8*)

: Data analysis example

    - slides: [Hurricane lizards](../CLASS_MATERIALS/Lectures/2020/Week_16_Hurricane_lizards.slides.html)
    - Group presentations

Week 17 (*2/15*)

: Factor analysis, dimensionality reduction, and visualization; clustering; PCA, PCoA, MDS, t-SNE, UMAP

    - slides: [Hurricane lizards, continued](../CLASS_MATERIALS/Lectures/2020/Week_16_Hurricane_lizards.slides.html)
    - slides: [Dimension reduction and PCA](../CLASS_MATERIALS/Lectures/2020/Week_17_Dimension_reduction_and_PCA.slides.html)
    - [Homework 17](../CLASS_MATERIALS/Homeworks/F20W21/HW17_W21.html) *(due 2/19)*
    - [Homework 18](../CLASS_MATERIALS/Homeworks/F20W21/HW18_W21.html) *(due 2/25)*

Week 18 (*2/22*)

: Latent factors, deconvolution for mixtures of expression data; nonnegative matrix factorization

    - slides: [t-SNE](../CLASS_MATERIALS/Lectures/2020/Week_17_tSNE.slides.html)
    - slides: [On ordination and dimension reduction methods](../CLASS_MATERIALS/Lectures/2020/Week_18_On_ordination.slides.html)
    - slides: [Nonnegative matrix factorization](../CLASS_MATERIALS/Lectures/2020/Week_18_Nonnegative_matrix_factorization.slides.html)
    - [Homework 19](../CLASS_MATERIALS/Homeworks/F20W21/HW19_W21.html) *(due 3/4)*

Week 19 (*3/1*)

: Deconvolution continued; introduction to spatial statistics and spatial autocorrelation.


    - slides: [Spatial autocorrelation](../CLASS_MATERIALS/Lectures/2020/Week_19_Spatial_autocorrelation.slides.html)
    - slides: [Spatial mapping](../CLASS_MATERIALS/Lectures/2020/Week_19_Biketown_maps.slides.html)
    - [Homework 20](../CLASS_MATERIALS/Homeworks/F20W21/HW20_W21.html) *(due 3/16)*

Week 20 (*3/8*)

: Spatial statistics: kernel density estimation and interpolation.

    - slides: [Spatial density estimation](../CLASS_MATERIALS/Lectures/2020/Week_20_Spatial_density_estimation.slides.html)
    - slides: [Spatial smoothing, and splines](../CLASS_MATERIALS/Lectures/2020/Week_20_Spatial_smoothing.slides.html)
    - slides: [Looking back: review](../CLASS_MATERIALS/Lectures/2020/Week_20_Review.slides.html)

