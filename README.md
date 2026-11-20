# 📈 Statistics with R

Statistics problems solved with **base R** – theory checked with simulation.
Code comments are in **German (A2 level)**.

## Topics
| # | Topic | Methods |
|---|---|---|
| 1 | Probability distributions | Binomial, Normal (`pbinom`, `pnorm`) |
| 2 | Central Limit Theorem | Monte-Carlo simulation |
| 3 | Confidence intervals | by hand vs. `t.test`, coverage simulation |
| 4 | Hypothesis tests | Welch & paired t-test, χ², ANOVA + Tukey HSD, Shapiro-Wilk, Wilcoxon |
| 5 | Correlation & regression | `cor.test`, `lm`, residual diagnostics |
| 6 | Bootstrap | CI for the median |
| 7 | Power analysis | `power.t.test` vs. simulation |

## Render
```r
install.packages("rmarkdown")
rmarkdown::render("statistics.Rmd")
```

## Skills
R · inferential statistics · simulation · experimental design · reproducible reports
