AI-Powered Supply Chain & Inventory Predictor

📌 Project Overview
This project addresses a critical business challenge: Inventory Stockouts and Overstocking. I built an end-to-end data pipeline that analyzes retail inventory levels, identifies high-risk products, and uses Predictive Analytics to recommend safety stock levels and reorder points.

🚀 Key Business Impact
Stockout Prevention: Identified products with a "Critical" status before they ran out.

Cost Optimization: Calculated Safety Stock and Reorder Points to minimize excess capital tied up in inventory.

Trend Analysis: Analyzed sales seasonality to predict future demand.

🛠️ Tech Stack & Tools
Language: Python (Pandas, NumPy, Scikit-Learn)

Visualization: Matplotlib, Seaborn (and Power BI - Coming Soon)

Database: SQL (MySQL) for data transformation

Version Control: Git & GitHub

📈 Analysis & Insights
1. Inventory Health Distribution
I engineered a Inventory_Status feature to categorize inventory.

Healthy: Sufficient stock for current demand.

Low: Needs monitoring.

Critical: Immediate reorder required to avoid lost revenue.

2. Demand Forecasting
Using Linear Regression, the system predicts sales for the next 7 days. This allows for proactive procurement rather than reactive purchasing.

3. Safety Stock & Reorder Logic
I implemented industry-standard formulas to help decision-makers:

Reorder Point = (Avg Daily Sales × Lead Time) + Safety Stock

📁 Project Structure
Plaintext
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks for EDA and Modeling
├── sql/                # SQL scripts for data processing
├── dashboard/          # Visualization exports and Power BI files
└── README.md           # Project documentation

🔧 How to Run
Clone the repo: git clone https://github.com/your-username/supply-chain-analysis.git

Install dependencies: pip install pandas scikit-learn matplotlib seaborn

Run the notebook: jupyter notebook notebooks/01_data_exploration.ipynb

📝 Future Work
[1] Integrate a Power BI Dashboard for real-time monitoring.

[2] Implement an LSTM Deep Learning model for more accurate time-series forecasting.

[3] Automate data ingestion via SQL.
