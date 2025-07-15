# Bitter Margins: Modeling the Gap Between Coffee Bean Costs and Retail Prices

**Author**: Hayeon Chung  
**Date**: July 15, 2025  

---

## Overview

Why do retail coffee prices keep climbing—even when wholesale bean prices drop?

**Bitter Margins** explores this question by modeling the relationship between wholesale bean costs and the price consumers pay at coffee shops. This project uses real-world economic data to quantify how much of the price is due to actual input costs versus other macroeconomic factors like inflation and time-based markup strategies.

---

## Key Objectives

- Investigate the relationship between wholesale bean prices and retail coffee prices.
- Adjust for inflation to examine real price trends over time.
- Evaluate whether markups have increased disproportionately.
- Apply statistical and machine learning models to understand key drivers of retail pricing.

---

## Methodologies Used

| Technique                  | Purpose                                                  |
|---------------------------|----------------------------------------------------------|
| **Multiple Linear Regression** | Predict retail coffee prices from bean cost and inflation |
| **ARIMA Time Series Forecasting** | Forecast future bean prices                              |
| **Random Forest**         | Rank feature importance in predicting retail prices      |

---

## Files in this Repo

| File                                                                 | Description                                         |
|----------------------------------------------------------------------|-----------------------------------------------------|
| `Bitter-Margins--Modeling-the-Gap-Between-Coffee-Bean-Costs-and-Retail-Prices.pdf` | Final knitted report of the full analysis           |
| `bitter_margins_analysis.Rmd`                                       | R Markdown file with code, modeling, and commentary |

> **Note**: Only the final `.Rmd` and knitted `.pdf` files are included. Raw data sources are publicly accessible and documented below.

---

## Key Insights

- Bean prices are volatile, but retail prices rise steadily.
- Inflation-adjusted retail prices show a mild upward trend.
- Markup ratios (retail/bean) have grown, suggesting increased margin capture.
- Regression results show both bean price and CPI significantly impact retail pricing.
- Random Forest analysis ranks **year** (time-based market behaviors) as the most important predictor—more than the actual bean cost.

---

## Data Sources

- **ICO Composite Indicator Price**: Coffee bean price index from the International Coffee Organization
- **Retail Prices by Country**: Global retail coffee prices (via Numbeo & Kaggle)
- **Inflation Index**: Country-level CPI data from the World Bank (rebased to 2010)

---

## License

This project is for educational and analytical purposes only. All rights to original data belong to their respective sources.
