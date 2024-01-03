# A Comparative Analysis of Bike Sharing in Dublin and Washington D.C.

## Abstract

This project aims to analyze and predict bike service trends in Dublin and Washington D.C. It employs the CRISP-DM framework and delves into four primary datasets. The data was acquired from trusted sources like data.gov.ie and Capital Bikeshare's official website, and reviews were sourced from TripAdvisor and Reddit through APIs. The datasets were cleaned and transformed to produce notable findings, including the distribution of bike stations, statistical analyses, and machine learning models.

**GitHub Repository Link**: [MSC_DA_CA2_Transport_Ireland](https://github.com/jmdtanalyst/MSC_DA_CA2_Transport_Ireland)

**Keywords**: population, transport, public, bike-sharing

**Word Count**: 2,843 words (excluding code, code comments, titles, references, and citations)

---

## Introduction

In recent years, bike-sharing systems have emerged as a popular and sustainable mode of transportation in urban areas. This project compares the usage of Dublin bikeshare systems against Capital bikeshare services.

### Project Description

For this project, the CRISP-DM framework was applied to ensure a structured approach to data analysis.

#### CRISP-DM Framework Steps:

1. **Business Understanding**: Analyze and understand people's experiences with bike-sharing services in Dublin and Washington DC.
2. **Data Understanding**: Focus on four datasets, including historical bike trips and reviews collected from TripAdvisor and Reddit.
3. **Data Preparation**: Clean, transform, and prepare datasets for analysis.
4. **Modeling**: Apply time-series analysis and machine learning algorithms for predictions.
5. **Evaluation**: Evaluate model performance using key metrics such as MSE and R^2 score.
6. **Deployment**: Deploy and save the model for future use.

---

## Data Preparation and Visualization

### 1. Data Acquisition:

- **DublinBikes**: Data collected from data.gov.ie.
- **Capital Bikeshare**: Data sourced from Capital Bikeshare's official website.
- **Reviews**: Data sourced from TripAdvisor and Reddit through APIs.

### 2. Data Cleaning and Engineering:

Datasets underwent cleaning, duplication removal, and null value handling. Statistical sampling was applied for efficient analysis.

### 3. Exploratory Data Analysis (EDA):

Visualizations were created using Plotly Express to analyze bike station distributions, trips by weekday, and sentiment analysis results.

---

## Statistics for Data Analytics

### 2.1 Descriptive Statistics:

Descriptive statistics were used to analyze patterns, trends, and relationships within the datasets.

### 2.2 Inferential Statistics:

Parametric and non-parametric tests were applied to compare bike trip proportions between Dublin and Washington D.C.

---

## Machine Learning for Data Analysis

### 3.1 Time Series Analysis:

Time-series analysis was applied using RandomForestRegressor, Linear Regression, and Ridge Regression algorithms.

### 3.2 Sentiment Analysis:

VADER was used for sentiment classification, achieving notable accuracies.

---

## Conclusion

This project offers valuable insights into bike-sharing systems in Dublin and Washington D.C., providing data-driven analyses and predictions that can inform urban transportation planning and policy-making.

---

For detailed information, code, and visualizations, please refer to the [GitHub Repository](https://github.com/jmdtanalyst/MSC_DA_CA2_Transport_Ireland).
