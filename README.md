# Term Deposit Marketing

### Prepared by: Japhet Hernández-Vaquero  
### Apziva 2024

## Overview

This project focuses on predicting potential customers for term deposits using a two-layer machine learning system. The primary goal is to maximize the identification of true positive customers and enhance precision in predicting both classes. Additionally, a SHAP (SHapley Additive exPlanations) analysis is conducted to identify key factors influencing subscription decisions, and a clustering approach is employed to segment customers who subscribed. Additionally, a Tableau Dashboard is included, you can watch the walkthrought in the video below:

<div align="center">
  <a href="https://www.youtube.com/watch?v=CzfJ8bHJGbQ">
    <img src="https://img.youtube.com/vi/CzfJ8bHJGbQ/0.jpg" alt="IMAGE ALT TEXT HERE">
  </a>
</div>

Also, two Power BI dashboards are shared in the following links:
* [ML Layer 2](https://github.com/JaphetHerzVaq/knvmZU6edHGjaMY/edit/main/README.md#:~:text=Term_Deposit_Marketing_Dashboard_ML_Layer2)
* [Customer Clustering](https://github.com/JaphetHerzVaq/knvmZU6edHGjaMY/edit/main/README.md#:~:text=Customer_clustering_dashboard)

## Key Highlights

1. **Two-Layer Machine Learning System**:
   - **Layer 1**: Aims to maximize the number of true class-1 customers correctly identified, highlighting potential subscribers.
   - **Layer 2**: Enhances precision in predicting both classes, focusing efforts on the most promising leads.

2. **SHAP Analysis**:
   - Identifies the most impactful features influencing the prediction of subscribers.
   - Positive impact: High call duration and predictions from Layer 1.
   - Negative impact: Short call duration and having a housing loan.

3. **Clustering Approach**:
   - Segments subscribers into distinct clusters using t-SNE and UMAP techniques.
   - Cluster 3 is identified as the most attractive segment, featuring customers with high call duration and high balance.

## Recommendations

### Short Term:
- Focus efforts on cold calling customers in Cluster 3.
- Emphasize calls on the 30th of each month, as conversions seem to double on this day.
- Implement campaign strategies targeting potential subscribers identified by the first prediction layer.
- Apply follow-up strategies on high-potential subscribers highlighted by the second prediction layer.

### Future Work:
- Analyze the content of longer calls, as these are more likely to result in subscriptions.
- Explore tools like Sentiment Analysis and Topic Analysis to gain insights into customer interactions and identify unmet needs.
