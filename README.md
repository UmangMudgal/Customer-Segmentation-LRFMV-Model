# Customet-Segmentation-LRFMV-Model

# Problem Statement : Customer Segmentation for Business Insights

# Background 
``In the era of data-driven decision-making, organizations accumulate vast amounts of historical data, including customer interactions, purchases, and behavioral patterns. Analyzing this data to uncover meaningful insights and identify distinct customer segments is crucial for optimizing business strategies, marketing campaigns, and overall performance.``

# Objective 
``The primary objective of this project is to leverage historical data to perform customer segmentation, thereby gaining deeper insights into customer behavior and preferences.``

# Proposed Solution : LRFMV Analysis for Enhanced Customer Segmentation
``The primary objective of this project is to leverage historical data to perform customer segmentation, thereby gaining deeper insights into customer behavior and preferences.``

In response to the need for improved customer segmentation and business insights, an innovative solution known as LRFMV (Length, Recency, Frequency, Monetary, Volume) Analysis has been propose by Mahfuza et. al(2022). This method builds upon the foundation of the widely used RFM (Recency, Frequency, Monetary) model while addressing its limitations and incorporating additional dimensions for a more comprehensive understanding of customer behavior and profitability.
** **
- **Key Enhancements**:

    **1. Length (L)**: Introduce the "Length" component to quantify the duration of a customer's relationship with the company. This crucial dimension captures the long-term and short-term dynamics of customer engagement, allowing us to differentiate between loyal, occasional, and new customers.

    **2. Volume (V)**: This component is introduced to bridge the gap between purchase quantity and profitability. By assessing the volume of purchases in relation to profit generated, we gain valuable insights into the customer's impact on the company's bottom line.

** **
- **Utilization of Unsupervised Clustering**

    - After the application of LRFMV Analysis, we employ the K-Means clustering algorithm to group customers into meaningful segments. The choice of the optimal number of clusters is made through a rigorous evaluation process. We utilize the Elbow method and Silhouette score to determine the most suitable number of clusters.


