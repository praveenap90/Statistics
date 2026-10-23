# 📊 Statistics Basics: An Interactive Guide for Analysts, Data Engineers & ML Practitioners

A single-file, dependency-free web app that teaches the statistics an analyst needs **before and during a project**. Every module pairs a short explanation (learning goals, key characteristics, ML context, why it matters) with something you can play with: sliders, simulators, calculators, and mini-games.

**Live demo:** enable GitHub Pages and open `index.html`.

---

## 🧭 Learning Objectives

After working through the app you will be able to:

* Frame a business problem with the 5 Ws and map stakeholders
* Tell metrics from KPIs and data types from each other
* Clean dirty data and choose honest, effective charts
* Summarize data and judge shape (skewness, kurtosis, outliers)
* Reason about probability, distributions, and uncertainty
* Run hypothesis tests and A/B test calculations
* Fit and diagnose regression models, and understand PCA
* Apply Bayesian updating and read time series
* Pick evaluation metrics and understand bias–variance

---

## 🗂️ Modules

The app has **8 main modules** with **25 lessons**. Pick a module in the top row, then a lesson in the second row; a Previous / Next button at the bottom walks you through everything in order. You can also link straight to a lesson, e.g. `index.html#regr`.

| # | Main module | Lessons | What you can do |
|---|---|---|---|
| 1 | **Foundations** | Business Problem · Metrics & KPIs · Types of Data | 5 Ws project-brief builder and stakeholder map; sort measures into KPIs vs metrics; classify columns |
| 2 | **Exploratory Data Analysis** | Data Wrangling · Descriptive Stats · Skew & Kurtosis · Visualization | Clean a messy dataset step by step; paste numbers for a full summary, boxplot and frequency table; 10-second dashboard test, chart chooser, 13-chart guide, formatting before/after |
| 3 | **Probability & Distributions** | Probability & Bayes · Distributions · CLT & Sampling | Bayes with natural frequencies; 7 distributions with sliders; sampling distributions and standard error |
| 4 | **Inference & Testing** | Confidence Intervals · A/B Test · Statistical Tests · Experiments | 50 simulated intervals; two-proportion z-test; Welch t-test and chi-square; sample size and power |
| 5 | **Relationships & Modeling** | Correlation · Regression · PCA | r and outliers; R², adjusted R² and residuals; principal components and scaling |
| 6 | **Bayesian & Time Series** | Bayesian · Time Series | Beta–Binomial updating; trend, seasonality and ACF |
| 7 | **Data Quality & ML Evaluation** | Data Quality · Bias–Variance · Metrics & CV | Scaling and imputation; under/overfitting; MSE/RMSE/MAE, log loss, k-fold |
| 8 | **Practice & Review** | SQL & pandas · Quiz · Flashcards | Click-to-copy snippets; 33-question quiz; 45 flashcards |

Every lesson opens with an **Explained** panel (learning goals, key characteristics, ML context, why it matters) followed by the interactive part.

---

## 🚀 Run or Publish

1. Save `index.html` in a repository.
2. In **Settings → Pages**, choose the branch and root folder.
3. Open the published URL. To use locally, just double-click `index.html`.

The concept maps use [Mermaid](https://mermaid.js.org/), loaded from a CDN, so they need an internet connection. Everything else works offline.

---

## 🛠 Tech Notes

* One HTML file, vanilla JavaScript, canvas charts. No build step, no tracking.
* Light and dark themes follow your system setting.
* Statistics verified against SciPy (Welch t-test, chi-square, log loss, sample-size formula).

---

## 🚧 Contributing

Ideas welcome: Bayes with more priors, survival analysis, causal-inference demos. ⭐ If you find this useful, consider giving it a star!
