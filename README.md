
# End-to-End Churn Analysis Portfolio Project

## Introduction to Churn Analysis
In today’s competitive business environment, retaining customers is crucial for long-term success. Churn analysis is a key technique used to understand and reduce customer attrition. It involves examining customer data to identify patterns and reasons behind customer departures.

By applying advanced data analytics and machine learning, businesses can predict which customers are at risk of leaving and understand the drivers behind churn. This enables companies to take proactive measures to improve customer satisfaction and loyalty.

## Project Objective
This project aims to develop a complete end-to-end churn analysis solution using a telecom dataset, including:

- ETL process in a relational database (SQL)
- Exploratory data analysis (EDA)
- Interactive visualization in Tableau Public
- Churn prediction using machine learning models (Python)

## Target Audience
Although this project is designed for a telecom dataset, the techniques and insights are applicable across industries such as retail, finance, healthcare, and subscription services.

Any business that values customer retention can benefit from understanding churn behavior and leveraging predictive analytics to inform strategy.

## Tools and Technologies
- Python: For data wrangling, EDA, and churn prediction modeling
- SQL: For ETL processes and database management
- Tableau Public: For building and publishing interactive dashboards
- Jupyter Notebook: For documentation and reproducibility

## Project Scope and Deliverables
This project includes:

- Data cleaning and exploration
- Database schema design and ETL pipeline (SQL scripts provided)
- Customer data analysis by:
  - Demographic factors
  - Geographic distribution
  - Payment and account information
  - Service subscriptions
- Churner profile analysis
- Identification of churn drivers
- Predictive model to forecast churn risk
- Interactive Tableau dashboard for business users

## Key Metrics
- Total customers
- Total churn and churn rate
- New customer joiners
- Demographic churn breakdown
- Service usage and churn patterns

## Business Value
This analysis enables proactive customer retention efforts by:

- Identifying churn-prone customer segments
- Understanding why customers churn
- Visualizing key trends to support business decisions
- Predicting future churners to reduce customer attrition

## Prediction and Insights

The analysis reveals a churn rate of approximately 27% across all customers. Month-to-month contracts are a significant churn predictor, with a churn rate exceeding 46%, compared to much lower churn rates for 1-year (11%) and 2-year (2.7%) contracts. 

Older customers (>50) are more likely to churn (31.6%), suggesting that retention strategies may need to be tailored for this demographic. Payment behavior is also correlated with churn: customers paying by mailed check or bank withdrawal have higher churn rates (37.8% and 34.4%, respectively) compared to those using credit cards (14.8%).

Fiber optic internet users exhibit a notably higher churn rate compared to customers on other internet services, highlighting a potential issue with service quality or expectations. Geographically, churn is highest in Jammu & Kashmir (57.2%), with other states such as Assam and Jharkhand also showing elevated rates.

Competitor-driven churn accounts for the largest proportion of churn reasons, indicating that competitive pressures are a major factor. The insights suggest focusing on converting month-to-month users to longer-term contracts, improving service quality for fiber internet customers, and developing retention offers tailored to older demographics and high-churn regions.

## How to Run This Project
1. Clone this repository:

2. Explore project files:
- SQL scripts in the `sql_scripts/` folder
- Python analysis notebooks in `notebooks/`
- Tableau workbook in `visualizations/` or access the Tableau Public link below

3. Tableau Dashboard:
This project’s interactive dashboard is published on Tableau Public.  
Link: [View the dashboard](https://public.tableau.com/app/profile/felicia.wijaya/viz/churnanalysis_17524691568160/Dashboard1)

## Next Steps
- Deploy a churn prediction API
- Automate ETL pipeline for production scenarios
- Include additional data sources such as customer service logs or web usage analytics

## Acknowledgments
Thanks to public churn datasets that inspired this project and open-source libraries and tools that enabled its development.


