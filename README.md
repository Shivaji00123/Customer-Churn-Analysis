# Customer-Churn-Analysis
I developed an interactive Power BI dashboard to analyze data, track key performance indicators (KPIs), identify trends, and generate meaningful business insights through dynamic visualizations. The project involved several stages, including data processing, data cleaning, and data visualization.

## Project Objective

The analysis focuses on evaluating customer demographics, subscription types, tenure, monthly charges, payment methods, and service-related complaints to identify which customer segments are more likely to discontinue their services.

## Data Collection

The dataset for this project was obtained from a publicly available online source. It was downloaded in Excel/CSV format and imported into SQL Server for data cleaning and preprocessing. After cleaning, the data was imported into Power BI to create interactive dashboards and identify important business insights.

### Tools Used
Microsoft Excel, Python, SQL Server, Power BI.

## Dataset Used 
- <a href="https://github.com/Shivaji00123/Customer-Churn-Analysis/blob/main/telco_churn_unclean.csv">Dataset</a>

## Questions (KPIs)
- What is the total number of customers?	
- How many customers have churned?	
- What is the overall customer churn rate?	
- What is the proportion of retained customers versus churned customers?
- Which customer tenure group has the highest churn rate?
- How many retained customers belong to Normal Risk and High Risk categories?
- How do average monthly charges compare between retained and churned customers?
- Which contract type has the highest number of churned customers?
- Which gender has the highest number of churned customers?
- How do monthly charges vary according to Online Security and Online Backup subscriptions?
- How does customer churn vary across different payment methods?

- Dashboard Interaction <a href="https://github.com/Shivaji00123/Customer-Churn-Analysis/blob/main/Customer%20Churn%20Analysis%20Dashoboard.png">View Dashboard</a>

## Process
- Collected a publicly available customer churn dataset, imported it into Microsoft Excel, and performed initial data exploration to understand the dataset structure, columns, and key business information.
- Imported the dataset into Jupyter Notebook and used Python libraries such as Pandas and NumPy to identify and handle missing values, remove duplicate records, and clean the dataset for accurate analysis
- Imported the cleaned dataset into SQL and performed queries to analyze customer churn patterns, customer distribution, tenure, contract types, and other key business metrics.
- Connected the analyzed data to Power BI and created interactive dashboards to visualize customer churn trends and identify important business insights.
- Created DAX measures such as Total Customers, Churned Customers, and Churn Rate. Developed calculated columns such as Tenure Band, Customer Type, and Risk Type to enable deeper customer segmentation and analysis.

## Dashboard
<img width="730" height="410" alt="Customer Churn Analysis Dashoboard" src="https://github.com/user-attachments/assets/b0c19480-3ae2-4e0c-8634-5f40069b2583" />


## Project Insight
Out of 7,036 customers, 1,868 customers (26.55%) discontinued their services, while 5,168 customers (73.45%) remained with the company.
number of male customers is 3551 out of that 929 are churned customers having churn rate 26.16% 
Number of female customers is 3485 out of that 939 are churned customers having churn rate 26.94% 
In the payment mode mode churned customer are using the Electronic Check Payment Method

## Conclusion
Female Customers Churn rate is slightly higher than Male customers churn rate by nearly 1%. The customers which uses Electronic Check Payment method has the highest Churn rate as out of 2363 Customers 1071 are the Churned Customers which makes the Churn rate about 45.32%.


