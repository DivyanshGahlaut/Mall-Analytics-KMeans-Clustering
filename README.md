# Mall-Analytics-KMeans-Clustering

"company": SkillCraft Technology

"NAME":DIVYANSH GAHLAUT

"INTERN ID" :SCT/JUN25/6158

"DOMAIN" :  Machine Learning

"DURATION": 4 WEEKS

*Project Description:

This project focuses on applying K-Means Clustering, an unsupervised machine learning algorithm, to analyze customer behavior data from a mall. The goal is to group customers into distinct segments based on features like age, annual income, and spending score. This segmentation allows businesses to better understand customer profiles, enhance marketing efforts, personalize offers, and improve customer satisfaction.

With meaningful clusters, retail businesses can:

Identify high-value customers.

Launch focused advertising campaigns.

Improve product placement and store layout.

Create tailored loyalty programs.

The project helps bridge the gap between raw data and strategic business decisions using machine learning.

*Tools & Technologies Used:

Python – Core programming language for development.

Pandas – For data loading, cleaning, and manipulation.

NumPy – To handle numerical operations and arrays.

Matplotlib & Seaborn – For creating interactive and insightful data visualizations.

Scikit-learn – Machine learning library used for implementing K-Means clustering.

Jupyter Notebook / VS Code – For writing, testing, and presenting code.

Kaggle – Source of the Mall Customer Dataset.

*How It Works:

1.Dataset Collection

The dataset is downloaded from Kaggle and contains information on 200 customers including:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

2.Data Preprocessing

Unnecessary columns are dropped (e.g., CustomerID)

Categorical features like Gender may be encoded if needed.

Features are scaled if necessary to improve clustering performance.

3.Exploratory Data Analysis (EDA)

Histograms, pair plots, and correlation heatmaps are created to understand the distribution and relationships between features.

Helps identify suitable features for clustering (commonly Annual Income and Spending Score).

4.Optimal Cluster Selection (Elbow Method)

The Elbow Method is used to find the ideal number of clusters (k) by plotting Within-Cluster Sum of Squares (WCSS).

The "elbow point" on the graph indicates the most balanced k.

5.K-Means Clustering

K-Means algorithm is applied to segment customers.

Each customer is assigned to one of the clusters.

6.Result Visualization

Clusters are visualized using 2D scatter plots.

Different colors represent different customer groups (e.g., low-income low-spenders, high-income high-spenders, etc.).

7.Insights and Business Use-Cases

Interpret the characteristics of each cluster.

Suggest how businesses can use this segmentation to:

Retain high-spending customers.

Upsell products to mid-spenders.

Create awareness campaigns for low-engagement customers.


