# electronicsales
Customer segmentation analysis of an electronic sales Kaggle dataset

📊 Electronic Sales Data Analysis (Sept 2023 – Sept 2024)
This project is a simple exploratory data analysis (EDA) and clustering task using a dataset of electronics sales spanning one year. The goal was to clean the data, explore customer behavior, visualize key trends, and group customers based on age and spending.

📁 Dataset Overview
The dataset  contains 20,000 rows and 16 columns. It includes customer demographic info (like age and gender), purchase behavior (total price, quantity), and other transaction-related fields.

🧰 Tools Used
Python

pandas, numpy

seaborn, matplotlib

scikit-learn (for clustering)

✅ Steps Taken
1. Data Cleaning & Preparation
Loaded the CSV file and checked its structure.

Filled in missing values:

Replaced missing Add-ons Purchased with 'None'

Replaced missing Gender with 'No Gender'

Dropped the Customer ID column, since it wasn't useful for analysis.

2. Exploratory Data Analysis (EDA)
We explored the dataset with a mix of summary stats and visualizations:

Distribution Plots: Age, Total Price, and Quantity

Gender Breakdown: Count of male vs. female customers

Violin Plots: Showing how age, price, and quantity vary across genders

Age Grouping: Grouped customers into 5 age brackets and plotted their counts

Spending Segments: Created price bands and visualized how many customers fall into each

Price vs. Age: Used scatter and hex plots to explore how spending varies with age

3. Customer Segmentation (K-Means Clustering)
We applied K-Means clustering to group customers by their age and total spending:

Standardized the features using StandardScaler

Used the Elbow Method to find an optimal number of clusters (we chose K = 4)

Visualized the resulting clusters and centroids

Printed out cluster sizes and centroids in original scale

