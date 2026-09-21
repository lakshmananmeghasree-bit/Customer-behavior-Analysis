Customer Behavior Analysis – Alfido Tech
📌 Project Overview

This project analyzes customer transaction data for Alfido Tech to understand customer behavior, purchasing patterns, customer segments, retention trends, and potential churn risks.

The analysis uses RFM (Recency, Frequency, Monetary) segmentation to group customers based on their purchasing behavior and identify opportunities for improving customer engagement and retention.

 🎯 Objectives

* Clean and prepare customer transaction data
* Engineer customer-level behavioral features
* Segment customers using RFM analysis
* Identify purchasing patterns and trends
* Analyze retention and churn across customer segments
* Provide actionable recommendations to improve customer engagement

 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* RFM Analysis

 📊 Analysis Methodology
1. Data Cleaning

* Checked for duplicate records
* Converted purchase dates into the appropriate date format
* Examined missing values
* Prepared transaction-level data for customer analysis

 2. Feature Engineering

Customer-level features were created using:

* Recency: Number of days since the customer's most recent purchase
* Frequency: Number of purchases made by the customer
* Monetary:Total amount spent by the customer

 3. Customer Segmentation

Customers were grouped into behavioral segments using RFM scores:

* 🏆 Champions
* 💙 Loyal Customers
* 🌱 New / Promising
* ⭐ Potential Loyalists
* ⚠️ At Risk
* 🔄 Lost / Hibernating

4. Purchase Pattern Analysis

The analysis examines:

* Revenue trends over time
* Product category performance
* Customer purchasing activity
* Customer segment distribution

 5. Retention & Churn Analysis

Customer segments were compared with the available churn information to identify differences in customer engagement and potential retention opportunities.

 🔍 Key Findings

* Champions show the strongest recent and frequent purchasing behavior with the highest average customer spend.
* Loyal Customers demonstrate strong repeat-purchase behavior and represent an important group for retention strategies.
* At Risk customers have relatively high historical purchase frequency and spending but have not purchased recently.
* Lost / Hibernating customers show low recent engagement and require selective reactivation campaigns.
* New / Promising customers provide an opportunity to increase long-term value by encouraging repeat purchases.

💡 Business Recommendations

1. Win back At-Risk customers
   Use personalized and time-limited offers based on previous purchasing behavior.

2. Reward Champions and Loyal Customers
   Introduce loyalty benefits, early access, and personalized recommendations to strengthen retention.

3. Reactivate Lost / Hibernating customers
   Run targeted reactivation campaigns and use incentives selectively based on customer value.

4. Convert New / Promising customers into repeat buyers
   Create post-purchase reminders, personalized recommendations, and second-purchase campaigns.

5. Monitor customer behavior continuously
   Track RFM segments, churn, categories, recency, and monthly customer activity through a recurring dashboard.

 📁 Repository Contents

| File                                       | Description                                                                                           |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| `Alfido_Tech_Customer_Analysis.ipynb`      | Complete Python analysis notebook with data processing, RFM segmentation, visualizations and insights |
| `Alfido_Tech_Customer_Analysis_Report.pdf` | Summary report containing key findings, segment profiles and recommendations                          |
| `customer.zip`                             | Dataset used for the analysis                                                                         |

 📈 RFM Segments

| Segment             | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| Champions           | Recent, frequent and high-value customers                    |
| Loyal Customers     | Customers with strong repeat purchasing behavior             |
| Potential Loyalists | Customers showing potential to become loyal                  |
| New / Promising     | Recently active customers with developing purchase behavior  |
| At Risk             | Previously valuable customers with declining recent activity |
| Lost / Hibernating  | Customers with low recent engagement                         |

 👩‍💻 Project Information

Project: Customer Transactions & Behavior Analysis
Organization: Alfido Tech
Analysis Type:Customer Segmentation & Behavioral Analytics
Method: RFM Analysis
Author: Lakshmanan Megha Sree

---

🔗 Project Files

 [📓 Analysis Notebook](./Alfido_Tech_Customer_Analysis.ipynb)
 [📄 Analysis Report](./Alfido_Tech_Customer_Analysis_Report.pdf)

---

**This project was completed as part of an Alfido Tech analytics internship task.**

