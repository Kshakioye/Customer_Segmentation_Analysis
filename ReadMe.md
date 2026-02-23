
#### Customer Segmentation Analysis using K-Means

**PROJECT OVERVIEW**

This project presents a customer segmentation analysis conducted as the final project of my Data Analytics internship at My Online Shop.

The objective was to identify distinct customer groups based on purchasing behavior and translate those insights into actionable strategies for personalization, marketing, and customer experience improvements in an e-commerce setting.

The analysis uses K-Means clustering on customer-level behavioral features to uncover natural groupings within the customer base.

**Business Objective**

The goal of this analysis was to:

- Identify meaningful customer segments
- Support data-driven personalization strategies
- Improve marketing efficiency and customer retention
- Allocate resources based on customer value and engagement

Rather than focusing purely on modeling complexity, the emphasis was on producing interpretable and actionable insights for business stakeholders.

**Dataset Description**

The dataset consisted of transaction-level e-commerce data. After cleaning and preprocessing, transactions were aggregated to the customer level.

Key Behavioral Features Used;

- RecencyDays – Days since the customer's last purchase
- PurchaseCount – Total number of purchases made
- TotalSpend – Total monetary value of purchases

These features capture each customer's RFM status - Recency, Frequency and Monetary value and consequently their Engagement, Loyalty and Vakue Contribution.

**Data Preparation**

The following preprocessing steps were performed:

Removal of cancelled or invalid transactions

Removal of negative prices and returns

Handling missing customer IDs

Outlier filtering where necessary

Aggregation from transaction-level to customer-level data

Feature scaling to normalize input for K-Means clustering

Scaling was essential because K-Means relies on distance calculations.

**METHODOLOGY**

**Feature Scaling & K-Means Clustering**

All behavioral features were scaled to ensure equal contribution to clustering and multiple values of K were tested.

Higher values of K produced small, non-actionable clusters.
A three-cluster solution (K=3) was selected because it provided:

     - Balanced segment sizes
     - Clear behavioral differentiation
     - Business interpretability
     - Actionable outcomes

**Customer Personas Identified**

The clustering results were translated into three intuitive personas:

1) *Gone-Cold*

                - Low purchase frequency
                - Low total spend
                - Long inactivity period
                - High churn risk

Business Strategy:
Selective reactivation campaigns, low-cost win-back promotions.

2) *Steady-Does-It*

                - Consistent purchasing behavior
                - Moderate spending
                - Relatively recent activity
                - Core revenue contributors

Business Strategy:
Retention efforts, loyalty programs, cross-selling and upselling opportunities.

3) *I Like It, I Buy It*

                - Very high purchase frequency
                - Extremely high spending
                - Highly recent activity 
                - Disproportionate revenue contribution

Business Strategy:
VIP treatment, personalized experiences, exclusive offers, priority support.

**Visualization**

Segment differences were summarized using bar charts comparing:

Average Recency

Average Purchase Count

Average Total Spend

Simple visual summaries were chosen to ensure clarity for both technical and non-technical stakeholders.

**Business Impact**

This segmentation framework enables:

 - Improved personalization
 - More efficient marketing budget allocation
 - Targeted retention strategies
 - Protection of high-value customers
 - Better understanding of churn risk

By linking segments to business metrics such as Customer Lifetime Value (CLV), churn risk, and revenue share, the analysis provides a strategic foundation for sustainable growth.

**TOOLS & TECHNOLOGY**

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

**KEY TAKEAWAY**

Customer segmentation delivers the most value when it balances analytical rigor with business usability. This project demonstrates how clustering techniques can be translated into practical strategies that drive personalization, retention, and revenue optimization.




**Author**

Shakioye Kofoworola . O
Data Analytics Intern – My Online Shop
LinkedIn Profile : www.linkedin.com/in/kofoworola-shakioye-1827a0291
