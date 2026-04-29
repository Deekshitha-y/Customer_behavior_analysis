📊 Customer Shopping Behavior Analysis

🔍 Overview

This project focuses on analyzing customer shopping behavior using transactional data to uncover meaningful insights that can drive business decisions. The analysis covers data preprocessing, exploratory data analysis (EDA), SQL-based business queries, and dashboard visualization using Power BI.

The objective is to understand customer segments, spending patterns, product preferences, and subscription behavior.

📁 Dataset
Total Records: 3,900 transactions
Total Features: 18 columns
Data includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavioral data (Discount usage, Purchase frequency, Ratings, Shipping type)
Missing Data:
37 missing values in Review Rating column (handled during preprocessing)

📌 Source: Based on retail transactional dataset used for customer behavior analysis

🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)
SQL (PostgreSQL)
Power BI (Interactive Dashboard)
Jupyter Notebook
Gamma (Presentation)

⚙️ Project Workflow

1. Data Loading & Exploration
Loaded dataset using Pandas
Performed initial analysis using:
df.info()
df.describe()

3. Data Cleaning & Preprocessing
Handled missing values using median imputation (category-wise)
Renamed columns to snake_case
Removed redundant column (promo_code_used)
Ensured data consistency

4. Feature Engineering
Created:
age_group (customer segmentation)
purchase_frequency_days
Improved data usability for analysis

5. SQL-Based Data Analysis
Data was stored in PostgreSQL and analyzed using SQL queries.

Key analyses performed:

Revenue comparison by gender
Identification of high-spending discount users
Top-rated products
Shipping type impact on purchase value
Subscriber vs non-subscriber comparison
Discount-dependent products
Customer segmentation (New, Returning, Loyal)
Top products by category
Repeat buyers vs subscription behavior
Revenue contribution by age group

📊 Dashboard (Power BI)

An interactive dashboard was developed to visualize key insights.

Key Metrics:
Total Customers: 3.9K
Average Purchase Amount: $59.76
Average Review Rating: 3.75
Dashboard Highlights:
Revenue by category
Sales distribution across age groups
Subscription analysis
Customer segmentation

📈 Results & Insights

Male customers generated higher revenue compared to female customers
Non-subscribers contributed more total revenue, despite similar average spend
Express shipping users tend to spend more than standard shipping users
Certain products (like hats and sneakers) are highly discount-driven
Majority of customers fall into the “Loyal” segment, indicating strong retention

💡 Business Recommendations

Improve subscription plans to increase adoption
Introduce loyalty programs for repeat customers
Optimize discount strategies to balance revenue and profit
Focus marketing on high-performing products and categories
Target high-revenue age groups for personalized campaigns

🚀 How to Run

1. Clone Repository

git clone https://github.com/deekshitha-y/Customer_behavior_analysis.git
cd customer-shopping-analysis

2. Install Dependencies
pip install pandas numpy matplotlib seaborn

3. Run Jupyter Notebook
jupyter notebook

4. SQL Setup
Import dataset into PostgreSQL
Execute SQL queries from scripts

5. Power BI
Open .pbix file
Refresh dataset to view dashboard

🎯 Key Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
SQL Query Optimization
Data Visualization
Dashboard Development
Business Insight Generation

📌 Conclusion
This project demonstrates a complete data analytics pipeline, from raw data processing to actionable insights and visualization. It highlights the ability to combine technical skills with business understanding, making it highly relevant for roles such as Data Analyst and Business Analyst.
