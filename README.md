# Mental Health and Income Inequality Analysis in India

## Project Overview

This project examines the relationship between socioeconomic inequality and mental health disorder prevalence across Indian states and union territories using statistical analysis.

The study uses the urban–rural Monthly Per Capita Consumption Expenditure (MPCE) gap as a proxy for inequality and investigates whether it is associated with reported mental health disorder prevalence.

## Objectives

- Examine the association between the urban–rural MPCE gap and mental health disorder prevalence.
- Apply statistical tests to investigate patterns and differences in the data.
- Use regression analysis to explore the relationship between the selected variables.
- Apply K-Means clustering to explore similarities among states and union territories.

## Tools and Technologies

- Python
- Pandas and NumPy
- SciPy
- Statsmodels
- Scikit-learn
- Statistical analysis and data visualization

## Methodology

The analysis includes:

- Descriptive statistical analysis
- Pearson correlation and Spearman rank correlation
- Regression analysis
- Hypothesis testing, including ANOVA and Kruskal–Wallis testing
- Levene's test
- K-Means clustering

## Key Findings

The analysis found a weak negative association between the urban–rural MPCE gap and mental health disorder prevalence.

- **Pearson correlation:** r = -0.247, p = 0.206
- **Spearman correlation:** ρ = -0.224, p = 0.252

Neither correlation was statistically significant at the 5% significance level. Therefore, the analysis does not provide sufficient evidence of a statistically significant association between the two variables in the study sample.

## Limitations

- The analysis covers 28 Indian states and union territories.
- Actual National Mental Health Survey prevalence figures were available for only 12 states; estimates or proxies were used for the remaining 16.
- The urban–rural MPCE gap is a partial proxy for inequality and does not capture every dimension of socioeconomic disadvantage.
- The cross-sectional analysis identifies associations and does not establish causation.
- The limited sample size restricts the conclusions that can be drawn.

## Repository Contents

- `report/` — Final project report.
- `notebooks/` — Analysis notebook, if included.
- `data/` — Shareable datasets or dataset access instructions, if included.
- `images/` — Selected project visualizations, if included.

## Disclaimer

The findings represent the results of this project's statistical analysis. They should not be interpreted as evidence that income inequality causes mental health disorders.
