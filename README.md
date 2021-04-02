# StatisticsR

** Very nice tutorials designed in UBC - [Visualizing statistics](https://www.zoology.ubc.ca/~whitlock/Kingfisher/KFhomepage.htm)**

[Sampling from a normal distribution](https://www.zoology.ubc.ca/~whitlock/Kingfisher/SamplingNormal.htm) - This app demonstrates the concept of a sampling distribution of an estimate, using the example of a mean of a normally distributed variable. It also reinforces the idea of a histogram.

Learning objectives:

- Visualize the meaning of the sampling distribution of the estimate of the mean.
- Understand that the distribution of sample means has the same mean as the mean of the population.
- Predict the relationship between sample size and the standard error.

[Confidence intervals for the mean](https://www.zoology.ubc.ca/~whitlock/Kingfisher/CIMean.htm) - This app shows the meaning of a confidence interval, calculating confidence intervals of the means of repeated samples.

Learning objectives:

- Understand the meaning of a confidence interval.
- Predict the effects of changing sample size on confidence intervals.

[Central limit theorem](https://www.zoology.ubc.ca/~whitlock/Kingfisher/CLT.htm) -- This app explores the sampling distribution of the mean when the data do not necessarily follow a normal distribution.

This app is designed to be used after the students are familiar with the general principles of sampling. The “Sampling from a normal distribution” app should perhaps be used first to introduce some of the basic concepts and the visual metaphors used here.

Learning objectives:

- Understand when the sample means of large samples will follow a normal sampling distribution, even when the variable is not normally distributed.
- Predict the effect of increasing or decreasing sample size on the normal approximation of the sample mean distribution.

[χ2 contingency analysis](https://www.zoology.ubc.ca/~whitlock/Kingfisher/ContingencyAnalysis.htm) - This app simulates samples of a 2x2 contingency analysis. It demonstrates that the χ2 test statistic follows a χ2 distribution and illustrates the meaning of the P-value. It may be most useful as a demonstration of the meaning of Type I error and power. This app has no tutorial version.

Learning objectives:

- Illustrate the meaning of the P-value associated with a contingency analysis (both with true and false null hypotheses).
- Demonstrate the meaning of Type I error.
- Show the meaning of power.
- Investigate the effects of sample size on power.

[]Robustness and power of the t test](https://shiney.zoology.ubc.ca/whitlock/RobustnessOfT/)

[Guessing correlation coefficients](https://shiney.zoology.ubc.ca/whitlock/Guessing_correlation/) - The correlation coefficient (r) describes the strength and direction of the association between two numerical variables. The goal of this page is to allow you to develop an intuition about how strong an association is implied by a given correlation coefficient. Each time you press the button marked "Simulate new data", the app will randomly choose a new correlation coefficient and randomly draw 30 data points with that r. Choose which of the three values best matches the correlation coefficient of the new data.

[Vizualizing residuals](https://shiney.zoology.ubc.ca/whitlock/Residuals/)
_________________________________________________________________________________________________________________________
The materials are taken from Statistical tools for high-throughput data analysis ([STHDA](http://www.sthda.com/english/))

**Section Summary:**

### [Normailty Test in R](https://github.com/yuliaUU/StatisticsR/blob/main/02-00-NormalityTestR.pdf)
Many of statistical tests including correlation, regression, t-test, and analysis of variance (ANOVA) assume some certain characteristics about the data. They require the data to follow a normal distribution or Gaussian distribution. These tests are called parametric tests, because their validity depends on the distribution of the data.
### [Statistical Tests and Assumptions](https://github.com/yuliaUU/StatisticsR/blob/main/03-00-StatisticalTests-andAssumptions.pdf)
Many of the statistical procedures including correlation, regression, t-test, and analysis of variance assume some certain characteristic about the data. Generally they assume that: 1) the data are normally distributed 2)and the variances of the groups to be compared are homogeneous (equal).
### [Comparing Means in R](https://github.com/yuliaUU/StatisticsR/tree/main/ComparingMeansR)
- Comparing one-sample mean to a standard known mean:
  - One-Sample T-test (parametric)
  - One-Sample Wilcoxon Test (non-parametric)
- Comparing the means of two independent groups:
  - Unpaired Two Samples T-test (parametric)
  - Unpaired Two-Samples Wilcoxon Test (non-parametric)
- Comparing the means of paired samples:
  - Paired Samples T-test (parametric)
  - Paired Samples Wilcoxon Test (non-parametric)
- Comparing the means of more than two groups
  - Analysis of variance (ANOVA, parametric):
    - One-Way ANOVA Test in R
    - Two-Way ANOVA Test in R
    - MANOVA Test in R: Multivariate Analysis of Variance
  - Kruskal-Wallis Test in R (non parametric alternative to one-way ANOVA)

