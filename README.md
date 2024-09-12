# User Engagement Analysis

## Overview

This Jupyter notebook is designed to perform **User Engagement Analysis** based on a telecom dataset. It focuses on understanding how users engage with various applications by analyzing their session frequency, session duration, and data traffic.

The goal of this analysis is to:
- Aggregate engagement metrics for each user.
- Report the top users by different engagement metrics.
- Cluster users based on their engagement patterns using k-means clustering.
- Visualize key findings to gain insights into user behavior.

### Key Metrics
We track the following key engagement metrics for each user:
- **Session Frequency**: The number of sessions initiated by the user.
- **Session Duration**: The total time the user spends in their sessions.
- **Total Traffic**: The total data usage (both download and upload traffic) during sessions.

### Analysis Tasks

#### 1. Aggregating Engagement Metrics
For each user (`MSISDN`), the notebook aggregates:
- Total session count.
- Total session duration.
- Total data traffic (download and upload).

#### 2. Top 10 Customers by Engagement
The top 10 customers are reported based on:
- Session frequency.
- Session duration.
- Total traffic.

#### 3. Clustering Users Based on Engagement
Using **k-means clustering**, users are grouped into clusters based on their normalized engagement metrics:
- **k=3** clusters are initially used.
- The **elbow method** is applied to find the optimal number of clusters.

#### 4. Per-Application Traffic Analysis
For each user, traffic is aggregated across different applications (e.g., Social Media, YouTube, Netflix). The top 10 most engaged users per application are reported, and the most used applications are visualized.

### Visualizations
- **Top 3 Most Used Applications**: Bar charts show the three applications with the highest traffic.
- **Elbow Method Plot**: This helps determine the optimal number of clusters for user segmentation.

### Clustering Insights
After grouping users into engagement clusters, the notebook computes summary statistics for each cluster, providing insights into the behavior of different user groups based on their engagement levels.

## Conclusion
This analysis helps telecom businesses identify highly engaged users and allocate network resources more efficiently, ensuring a high-quality user experience. By clustering users into engagement groups, network teams can focus on improving performance for key customer segments.