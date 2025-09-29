Customer Churn Reduction Analysis (Telecom Industry) 📞📉
🎯 Project Goal
The primary goal of this project was to identify the specific behavioral segment within the high-risk "Non-Renewing" customer base that drives the highest churn rate. The outcome is a quantified, actionable recommendation designed to maximize Annual Recurring Revenue (ARR) retention.

💡 Key Finding & Business Impact
The analysis successfully isolated a critical segment—customers who Did Not Renew their contract AND experienced 4 or more customer service calls (High Service Friction)—and demonstrated its disproportionate impact on churn.

Segment	Churn Rate	Impact
High Friction (≥4 Calls)	67.86%	27.86 percentage points higher than the low-friction group.
Low/Moderate Friction (<4 Calls)	40.00%	

Export to Sheets
Quantified Recommendation:
Implementing a priority support intervention for the 28 high-friction customers is projected to save over $7,500 in Annual Recurring Revenue (ARR) by reducing their churn rate.

💻 Project Structure & Methodology
This project followed a standard data science methodology, utilizing Python for analysis and Tableau for professional data visualization.

1. Data Segmentation (Python)
The Untitled.ipynb notebook performs the core analysis:

Isolation: Filtered the dataset to isolate the 323 customers who did not renew their contracts (ContractRenewal=0).

Feature Engineering: Created the Service_Friction segmentation column based on the number of customer service calls (CustServCalls).

Quantification: Calculated the churn rate for the high-friction group (67.86%) and computed the potential ARR savings.

2. Visualization (Tableau)
The analysis was visualized to clearly show the risk gap:

Visualization: A filtered bar chart comparing the churn rate of the High Friction vs. Low/Moderate Friction groups.

Deliverable: The final dashboard includes the visual evidence and the quantified recommendation text.

📁 Repository Files
File	Description
Untitled.ipynb	The complete Python (Jupyter) notebook containing all data loading, feature engineering, analysis, and quantification logic.
telecom_churn.csv	The original raw dataset used for analysis.
FINAL_CHURN_DATA_FOR_TABLEAU.csv	The final dataset exported from Python, which includes the engineered Service_Friction column, ready for Tableau visualization.
Telecom_Churn_Analysis_Final.twbx	The Tableau packaged workbook file containing the final dashboard design and chart layout.
