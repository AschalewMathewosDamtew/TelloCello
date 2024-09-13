# Customer Satisfaction Analysis

This repository contains the analysis of customer satisfaction based on engagement and experience metrics. The analysis is performed in the `satisfaction_analysis.ipynb` notebook and includes several tasks as outlined below.

## Tasks

### Task 4.1: Calculate Engagement and Experience Scores

The engagement and experience scores are calculated for each user based on their Euclidean distance to the respective clusters.

- **Engagement Score**: Calculated as the Euclidean distance between the user data point and the least engaged cluster from the initial clustering analysis.
- **Experience Score**: Calculated as the Euclidean distance between the user data point and the worst experience cluster.

### Task 4.2: Calculate Satisfaction Score

The satisfaction score for each customer is derived as the average of the engagement and experience scores. The top 10 satisfied customers are identified based on this score.

### Task 4.3: Predict Satisfaction Score

A regression model is built to predict the satisfaction score of a customer based on engagement and experience metrics.

### Task 4.4: K-Means Clustering on Scores

K-means clustering with `k=2` is applied to the engagement and experience scores to identify clusters of customers based on their satisfaction and experience levels.

### Task 4.5: Aggregate Scores by Cluster

The average satisfaction and experience scores are aggregated per cluster to understand the overall performance and satisfaction level within each cluster.

## Files

- `satisfaction_analysis.ipynb`: Jupyter Notebook containing the analysis and implementation of the tasks.

## Setup

1. **Install Dependencies**: Make sure to have the required libraries installed. You can install them using pip:

    ```bash
    pip install requirements.txt
    ```

2. **Run Notebook**: Open the `satisfaction-analysis.ipynb` notebook and execute the cells to perform the analysis.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.