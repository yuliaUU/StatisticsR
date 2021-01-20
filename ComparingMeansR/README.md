
## Comparing one-sample mean to a standard known mean
### [One-sample T-test (parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-01-One-SampleT-testR.pdf)
- What is one-sample t-test?
- Research questions and statistical hypotheses
- Formula of one-sample t-test
- Visualize your data and compute one-sample t-test in R
  - R function to compute one-sample t-test
  - Visualize your data using box plots
  - Preliminary test to check one-sample t-test assumptions
  - Compute one-sample t-test
  - Interpretation of the result

### [One-sample Wilcoxon test (non-parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-02-One-SampleWilcoxonSignedRankTestR.pdf)
- What’s one-sample Wilcoxon signed rank test?
- Research questions and statistical hypotheses
- Visualize your data and compute one-sample Wilcoxon test in R
  - R function to compute one-sample Wilcoxon test
  - Visualize your data using box plots
  - Compute one-sample Wilcoxon test

## Comparing the means of two independent groups
### [Unpaired two samples t-test (parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-03-UnpairedTwo-SamplesT-testR.pdf)
- What is unpaired two-samples t-test?
- Research questions and statistical hypotheses
- Formula of unpaired two-samples t-test
- Visualize your data and compute unpaired two-samples t-test in R
  - R function to compute unpaired two-samples t-test
  - Visualize your data using box plots
  - Preliminary test to check independent t-test assumptions
  - Compute unpaired two-samples t-test
- Interpretation of the result

### [Unpaired two-samples Wilcoxon test (non-parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-04-UnpairedTwo-SamplesWilcoxonTestR.pdf)
- R function to compute Wilcoxon test
- Visualize your data using box plots
- Compute unpaired two-samples Wilcoxon test

## Comparing the means of paired samples
### [Paired samples t-test (parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-05-PairedSamplesT-testR.pdf)
### [Paired samples Wilcoxon test (non-parametric)](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-06-PairedSamplesWilcoxonTestR.pdf)

## Comparing the means of more than two groups
### [One-way ANOVA test](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-07-One-WayANOVATestR.pdf)
An extension of independent two-samples t-test for comparing means in a situation where there are more than two groups.

- What is one-way ANOVA test?
- Assumptions of ANOVA test
- How one-way ANOVA test works?
  - Visualize your data and compute one-way ANOVA in R
  - Visualize your data
  - Compute one-way ANOVA test
  - Interpret the result of one-way ANOVA tests
  - Multiple pairwise-comparison between the means of groups
    - Tukey multiple pairewise-comparisons
    - Multiple comparisons using multcomp package
    - Pairwise t-test
  - Check ANOVA assumptions: test validity?
    - Check the homogeneity of variance assumption
    - Relaxing the homogeneity of variance assumption
    - Non-parametric alternative to one-way ANOVA test
    - Check the normality assumption
  - Non-parametric alternative to one-way ANOVA test

### [Two-Way ANOVA test](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-08-Two-WayANOVATestR.pdf)
- What is two-way ANOVA test?
- Two-way ANOVA test hypotheses
- Assumptions of two-way ANOVA test
- Compute two-way ANOVA test in R: balanced designs
  - Visualize your data
  - Compute two-way ANOVA test
  - Interpret the results
  - Compute some summary statistics
  - Multiple pairwise-comparison between the means of groups
    - Tukey multiple pairewise-comparisons
    - Multiple comparisons using multcomp package
    - Pairwise t-test
  - Check ANOVA assumptions: test validity?
    - Check the homogeneity of variance assumption
  - Check the normality assumption
- Compute two-way ANOVA test in R for unbalanced designs

## [MANOVA test: Multivariate analysis of variance](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-09-MANOVA-TestR-MultivariateAnalysisofVariance.pdf)
- What is MANOVA test?
- Assumptions of MANOVA
- Interpretation of MANOVA
- Compute MANOVA in R

## [Kruskal-Wallis test](https://github.com/yuliaUU/StatisticsR/blob/main/ComparingMeansR/01-10-Kruskal-WallisTestR.pdf)
- What is Kruskal-Wallis test?
- Visualize your data and compute Kruskal-Wallis test in R
- Visualize the data using box plots
- Compute Kruskal-Wallis test
- Multiple pairwise-comparison between groups
