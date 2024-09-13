# Telecom Data Analysis Suite

## Overview

This repository contains multiple projects focused on analyzing telecom data to gain insights into user behavior, application usage, network performance, and customer satisfaction. The analyses are carried out in separate branches, each dedicated to specific aspects of telecom data.

## Branches

### 1. Telecom Data Analysis

- **Description**: This branch involves analyzing telecom data with a focus on user behavior, application usage, and dimensionality reduction.
- **Key Analysis Tasks**:
  - **Top Handsets and Manufacturers Analysis**: Identifying top handsets and manufacturers.
  - **Exploratory Data Analysis (EDA)**: Segmenting users, calculating basic metrics, and performing univariate analysis.
  - **Graphical Univariate Analysis**: Visualizing distributions using histograms.
  - **Bivariate Analysis**: Exploring relationships between application data usage and total data usage.
  - **Correlation Analysis**: Analyzing correlations between different applications.
  - **Dimensionality Reduction**: Applying PCA for dimensionality reduction and visualization.

### 2. User Engagement Analysis

- **Description**: This branch focuses on user engagement metrics, clustering users, and visualizing engagement patterns.
- **Key Analysis Tasks**:
  - **Aggregating Engagement Metrics**: Total session count, duration, and traffic for each user.
  - **Top Customers**: Reporting top 10 customers based on session frequency, duration, and traffic.
  - **Clustering**: Using k-means clustering to group users based on engagement metrics.
  - **Per-Application Traffic Analysis**: Analyzing traffic by application and reporting top users per application.

### 3. Mobile Network Data Analysis

- **Description**: This branch analyzes mobile network performance, focusing on handset types, throughput, and retransmission volumes.
- **Key Analysis Tasks**:
  - **Top, Bottom, and Most Frequent Values**: Identifying handsets with highest/lowest throughput and retransmissions.
  - **Visualizing Throughput & Retransmission**: Bar plots for average throughput and TCP retransmissions.

### 4. Customer Satisfaction Analysis

- **Description**: This branch analyzes customer satisfaction based on engagement and experience metrics, including clustering and prediction tasks.
- **Key Analysis Tasks**:
  - **Calculate Engagement and Experience Scores**: Using Euclidean distance to cluster scores.
  - **Calculate Satisfaction Score**: Deriving satisfaction score as an average of engagement and experience scores.
  - **Predict Satisfaction Score**: Building a regression model for prediction.
  - **K-Means Clustering on Scores**: Clustering customers based on satisfaction scores.
  - **Aggregate Scores by Cluster**: Analyzing average satisfaction and experience scores per cluster.

## Getting Started

1. **Install Dependencies**: Ensure you have the required libraries installed. Use:
    ```bash
    pip install -r requirements.txt
    ```

2. **Running the Notebooks**: Open the respective Jupyter notebooks (`*.ipynb` files) in each branch and execute the cells to perform the analysis.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [aschalewthecoder@gmail.com](mailto:aschalewthecoder@gmail.com).

---

**Project Status**: Active  
**Last Updated**: September 2024  
**Contributors**: [thecodr](https://thecodr-portfolio.vercel.app)  
**Acknowledgments**: Special thanks to [Data Source](https://drive.google.com/drive/folders/1y40EiCZjY3NliqpRl2ZnPMV5X4qKz7T1?usp=sharing) for providing the dataset used in this analysis.
