# Gender Role Attitudes and Life Satisfaction

Cross-national analysis using World Values Survey (Wave 7) data (~11,000
respondents, 6 countries). Tests whether gender-role attitudes relate to life
satisfaction, and whether that relationship is moderated by country.

**Methods:** OLS regression, interaction/moderation model with F-test,
cluster-robust standard errors, residual/VIF diagnostics, ordinal logistic
regression robustness check.

**Files:**
- `WVS_Gender_Attitudes_LifeSatisfaction.Rmd` — full analysis (source)
- `WVS_Gender_Attitudes_LifeSatisfaction.pdf` — knitted report

**To reproduce:** download `WVS_Cross-National_Wave_7_csv_v6_0.csv` from the
[World Values Survey site](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp),
place it alongside the `.Rmd`, and knit in RStudio.

**Packages required:** tidyverse, gridExtra, broom, estimatr, car, MASS, modelsummary
