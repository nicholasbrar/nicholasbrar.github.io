---
layout: page
title: Consumption Model
description: High performance log-linear regression model
img:
importance: 2
category: work
related_publications: false
---

The CEX Model Generator is a regression engine I built to predict household consumption patterns by mapping demographic variables—income, household size, education, and more—to spending across a wide range of categories. When I inherited the legacy approach (a 1-year, 6-feature R model scaled by CPI), I saw an opportunity to do a lot better. I rewrote it from the ground up in Python, pulling in 16 years of Consumer Expenditure Survey data (2007–2023) and designing a modular feature engineering "factory" that made experimenting with new variables fast and repeatable. The result was a meaningful performance lift—an average R² improvement of 0.08 per consumption category.
I built the pipeline to handle the entire model lifecycle: raw CEX data ingestion, outlier cleaning, weighted regression training with flexible feature toggling, and a dedicated validation suite that stress-tests predictions against real-world income and expenditure constraints. The coefficients this system produces serve as the foundational logic for the CBEI system, which uses them to estimate regional carbon footprints and household-level emissions from census data.

