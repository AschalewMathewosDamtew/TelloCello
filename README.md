# Telecom Data Analysis

## Overview

This project involves analyzing telecom data to gain insights into user behavior and application usage. The analysis includes univariate and bivariate statistics, correlation analysis, and dimensionality reduction using PCA.

## Data

The dataset used in this project is `telecom_data.xlsx`, which contains various metrics related to telecom usage, including data download and upload volumes for different applications.

## Analysis Tasks

### 1. Top Handsets and Manufacturers Analysis

- Identified the top 10 handsets and top 3 manufacturers based on the number of occurrences.
- Determined the top 5 handsets for each of the top 3 manufacturers.

### 2. Exploratory Data Analysis (EDA)

- Described relevant variables.
- Segmented users into deciles based on total session duration and visualized the total data usage per decile.
- Calculated basic metrics such as mean and median for key variables.
- Performed non-graphical univariate analysis by computing variance and standard deviation for numeric columns.

### 3. Graphical Univariate Analysis

- Plotted histograms for various metrics to understand their distributions.

### 4. Bivariate Analysis

- Created scatter plots to explore the relationship between application data usage and total data usage.

### 5. Correlation Analysis

- Analyzed the correlation matrix for application data usage to identify relationships between different applications.

### 6. Dimensionality Reduction

- Applied Principal Component Analysis (PCA) to reduce the dimensionality of application data usage and visualized the results.

## Usage

1. Ensure that the required libraries are installed. You can install them using:
   ```bash
   pip install -r requirements.txt
