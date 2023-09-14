# Customet-Segmentation-LRFMV-Model

# Problem Statement : Customer Segmentation for Business Insights

# Background 
In the era of data-driven decision-making, organizations accumulate vast amounts of historical data, including customer interactions, purchases, and behavioral patterns. Analyzing this data to uncover meaningful insights and identify distinct customer segments is crucial for optimizing business strategies, marketing campaigns, and overall performance.

# Objective 
The primary objective of this project is to leverage historical data to perform customer segmentation, thereby gaining deeper insights into customer behavior and preferences.

# Proposed Solution : LRFMV Analysis for Enhanced Customer Segmentation
The primary objective of this project is to leverage historical data to perform customer segmentation, thereby gaining deeper insights into customer behavior and preferences.

In response to the need for improved customer segmentation and business insights, an innovative solution known as LRFMV (Length, Recency, Frequency, Monetary, Volume) Analysis has been propose by Mahfuza et. al(2022). This method builds upon the foundation of the widely used RFM (Recency, Frequency, Monetary) model while addressing its limitations and incorporating additional dimensions for a more comprehensive understanding of customer behavior and profitability.
** **
- **Key Enhancements**:

    **1. Length (L)**: Introduce the "Length" component to quantify the duration of a customer's relationship with the company. This crucial dimension captures the long-term and short-term dynamics of customer engagement, allowing us to differentiate between loyal, occasional, and new customers.

    **2. Volume (V)**: This component is introduced to bridge the gap between purchase quantity and profitability. By assessing the volume of purchases in relation to profit generated, we gain valuable insights into the customer's impact on the company's bottom line.

** **
- **Utilization of Unsupervised Clustering**

    - After the application of LRFMV Analysis, we employ the K-Means clustering algorithm to group customers into meaningful segments. The choice of the optimal number of clusters is made through a rigorous evaluation process. We utilize the Elbow method and Silhouette score to determine the most suitable number of clusters.

** **
# Key Term Defination 

**1. Recency (R):**
   - **Definition:** Recency refers to how recently a customer has interacted or made a purchase with the company. It measures the time elapsed since the last customer activity.

**2. Frequency (F):**
   - **Definition:** Frequency represents how often a customer engages with the company or makes purchases. It quantifies the customer's repeated interactions.

**3. Monetary (M):**
   - **Definition:** Monetary reflects the monetary value of a customer's purchases or transactions. It measures the amount of money spent by the customer.

**4. Length (L):**
   - **Definition:** Length, introduced in the LRFMV model, measures the duration or length of a customer's relationship with the company. It assesses both the short-term and long-term engagement.

**5. Volume (V):**
   - **Definition:** Volume, also introduced in the LRFMV model, evaluates the volume or quantity of a customer's purchases. It considers the quantity of items bought or the scale of transactions and relates to the Profitablity.

** **

# Segmentation Description of Classes
# Segmentation Description of Classes

# Segmentation Description of Classes

| Customer Class                       | Recency  | Frequency | Monetary | Length | Volume | Description                                                                                                                            |
| ----------------------------------- | -------- | --------- | -------- | ------ | ------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| One-time Customer                    | High     | Low       | Low      | Low    | Low    | Customers who made a purchase a long time ago, with low frequency, monetary value, and product volume.                                |
| Loyal Customers                      | Low      | High      | High     | High   | Low    | Customers who are actively engaged in purchasing for extended periods, even though they buy a lower quantity of products.             |
| VIP Customer                         | Low      | High      | High     | High   | High   | Customers with a long relationship with the company, high spending power, and a high volume of purchased products.                   |
| Past Transactional Driven Customer   | High     | High      | High     | Low    | High   | Customers who have made a significant number of purchases but have not bought anything recently.                                      |
| New Customer                         | Low      | Low       | Low      | Low    | Low    | Customers who have recently made a purchase with a low volume of purchases.                                                            |


