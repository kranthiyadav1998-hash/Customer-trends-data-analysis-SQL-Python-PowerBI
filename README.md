Customer Shopping Behavior Analysis
📌 Overview
This project provides an end-to-end data analytics solution to understand consumer purchase patterns. By leveraging Python for data engineering, SQL for deep-dive analysis, and Power BI for visualization, this project transforms raw transactional data into actionable business strategies for the retail sector.

📊 Dataset
The analysis is based on a Customer Shopping Behavior dataset containing 3,900 records.

Key Features: Age, Gender, Purchase Amount, Item Category, Subscription Status, Shipping Type, and Review Ratings.

Objective: To identify high-value segments and optimize marketing/inventory strategies.

🛠 Tools & Technologies
Language: Python 3.14 (Pandas, NumPy, Jupyter Notebook)

Database: PostgreSQL (or MySQL/SQL Server) for structured querying

BI Tool: Power BI (Data Modeling & Dashboarding)

AI Integration: Gemini (Slide Deck Generation & Report Drafting)

Environment: Windows-based local development

🚀 Project Steps
1. Data Cleaning & EDA (Python)
Standardized column names to snake_case.

Handled missing values in Review Rating using category-specific median imputation.

Performed Exploratory Data Analysis to identify outliers and distributions.

Segmented customers into Age Groups (Young Adult, Adult, Senior).

2. Database Management (SQL)
Migrated cleaned CSV data into a relational database.

Wrote complex queries to calculate:

Total revenue by gender and category.

Percentage of purchase amounts using Window Functions.

Subscription conversion rates.

3. Business Intelligence (Power BI)
Connected Power BI to the SQL database.

Created a Star Schema data model.

Developed DAX measures for YTD Sales and Average Transaction Value.

4. Generative AI (Gemini)
Utilized Gemini to analyze summary statistics and generate a professional 12-slide PowerPoint presentation.

Drafted a final executive summary report based on visual insights.

📈 Dashboard Highlights
The Power BI Dashboard includes:

Executive Summary: High-level KPIs (Total Revenue, Avg Rating, Total Orders).

Demographic Insights: Revenue breakdown by Age and Gender.

Behavioral Analysis: Discount usage vs. Purchase frequency.

Logistics Tracking: Shipping type performance and spend correlation.

🏆 Key Results
Top Performers: Jewelry and Clothing items (Blouses, Pants) drive the highest volume.

Revenue Drivers: The "Young Adult" segment is the most profitable cohort ($62k+ revenue).

Growth Opportunity: 73% of customers are currently non-subscribers, representing a massive target for loyalty programs.

Quality Leaders: Accessories (specifically Gloves) hold the highest customer satisfaction ratings.

💻 How to Run
Clone the Repo:

Bash
git clone https://github.com/yourusername/shopping-behavior-analysis.git
Setup Python:

Install dependencies: pip install pandas sqlalchemy psycopg2.

Run the data_cleaning.ipynb notebook.

Database Setup:

Import the cleaned_data.csv into your SQL instance.

Execute the queries found in /sql/analysis_queries.sql.

Visualize:

Open the .pbix file in Power BI Desktop to view the interactive dashboard.
