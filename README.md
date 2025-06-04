Telecom Customer Segmentation Using K-Means Clustering
This project delivers a data-driven analysis of telecom user engagement based on traffic behavior across popular applications (YouTube, Google, Email, Netflix, Gaming, Others). Using K-Means clustering, customers are segmented by activity level to uncover behavioral patterns and generate actionable insights for customer targeting and service optimization.

🚀 Project Objectives
Customer Engagement Aggregation

Aggregate upload/download traffic per customer (MSISDN) and application.

Rank top 10 customers by engagement per app.

Data Normalization & K-Means Segmentation

Normalize traffic metrics for comparability.

Apply K-Means clustering to segment users into 3 engagement tiers.

Analyze min, max, average, and total metrics per cluster.

Application Usage Insights

Measure total traffic per application.

Highlight top users per application.

Usage Trends Visualization

Identify and plot the top 3 most-used applications.

Cluster Optimization (Elbow Method)

Determine the optimal number of clusters using the Elbow Method.

🗂️ Project Structure
bash
Copy
Edit
TellCo-Telecom-Analytics/
├── data/             # Raw and cleaned data files
├── notebooks/        # Jupyter notebooks for analysis
├── src/              # Python modules for preprocessing & clustering
├── reports/          # Visualizations and summary reports
├── requirements.txt  # Dependency list
└── README.md         # Project documentation
⚙️ Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/gworku/TellCo-Telecom-Analytics-.git
cd TellCo-Telecom-Analytics-
Create a Virtual Environment

bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
Add Data Files

Place your raw telecom data into the data/ directory.

Launch Notebooks

bash
Copy
Edit
jupyter notebook notebooks/
