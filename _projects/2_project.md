---
layout: page
title: Consumption Model
description: High performance log-linear regression model
img: assets/img/3.jpg
importance: 2
category: work
related_publications: false
---

The CEX Model Generator is a high-granularity regression engine that predicts household consumption patterns by mapping demographic variables—such as income, household size, and education—to spending across diverse categories. This module evolved the legacy approach (a 1-year, 6-feature R model scaled by CPI) into a sophisticated Python-based pipeline. By implementing multi-year data aggregation (2007–2023) and a modular feature engineering "factory," the system achieved a significant performance lift, increasing $R^2$ by an average of 0.08 per consumption category.The automated workflow handles the entire lifecycle of model development, from raw Consumer Expenditure Survey (CEX) data preparation and outlier cleaning to weighted regression training with flexible feature toggling. To ensure accuracy, the system includes a dedicated validation suite that tests predictions against real-world income and expenditure constraints. The resulting coefficients are the primary output, providing the foundational logic used by the CBEI system to estimate regional carbon footprints and household-level emissions based on census data.

