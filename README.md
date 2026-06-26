# Statistical-Analysis-of-Movie-Box-Office
Statistical analysis of worldwide movie box office data using R, including regression modelling, PCA and clustering.
# Statistical Movie Box Office Analysis

Statistical analysis of worldwide movie box office data using **R**, completed as part of an undergraduate statistics project.

---

## Project Overview

The objective of this project is to explore the determinants of movie box office performance through statistical analysis and data modelling.

Using a dataset containing information on worldwide movie revenues, budgets, genres, production countries and other characteristics, the project applies both descriptive and inferential statistical methods to better understand factors associated with commercial success.

---

## Objectives

* Explore the structure of the movie industry through descriptive statistics.
* Study relationships between financial variables using regression models.
* Identify underlying patterns using Principal Component Analysis (PCA).
* Group similar movies using K-means clustering.
* Evaluate the strengths and limitations of statistical models for real-world data.

---

## Dataset

The dataset contains information on thousands of commercially released movies, including variables such as:

* Worldwide Box Office Revenue
* Budget
* Opening Weekend Revenue
* Genre
* Production Country
* Language
* Production Company
* Creative Type

Missing values were handled during the preprocessing stage before statistical analysis.

---

## Methodology

### Data Preprocessing

* Data cleaning
* Missing value handling
* Variable transformation
* Feature engineering
* Log transformation for highly skewed variables

### Exploratory Data Analysis

* Summary statistics
* Histograms
* Density plots
* Boxplots
* Correlation analysis
* Distribution comparison

### Regression Analysis

Linear regression models were developed to investigate the relationship between box office revenue and several explanatory variables, including:

* Budget
* Opening Weekend Revenue
* Legs (box office multiplier)

Model assumptions were evaluated using diagnostic plots, including:

* Residuals vs Fitted
* Normal Q-Q Plot
* Scale-Location Plot
* Cook's Distance

---

### Principal Component Analysis (PCA)

PCA was performed to:

* Reduce data dimensionality
* Study relationships between quantitative variables
* Visualize movie distributions in lower-dimensional space

---

### K-means Clustering

K-means clustering was applied to identify groups of movies with similar statistical characteristics.

Different numbers of clusters were evaluated before selecting the final clustering solution.

---

## Tools

* R
* R Markdown

---

## Main Findings

* The dataset is highly right-skewed due to the presence of blockbuster movies.
* Opening Weekend Revenue is one of the strongest predictors of total worldwide revenue.
* PCA highlights strong correlations among several financial indicators.
* Clustering reveals different profiles of movie performance rather than a single homogeneous market.

---

## Repository Structure

```text
Movie-Box-Office-Analysis-R
│
├── README.md
├── TopMovies.Rmd
├── Report.pdf
```

---

## Author

**Zhehui ZHOU**

Undergraduate student in **MIASHS (Mathematics and Computer Science Applied to Humanities and Social Sciences)**
Université Paris Cité

**Interests**

* Applied Statistics
* Data Analysis
* Econometrics
* Mathematical Modelling
* Machine Learning
