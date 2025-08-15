# Mall_Customer_Segmentation
Mall Customer Segmentation using Machine Learning
📌 Project Overview

This project performs customer segmentation for a mall's dataset using unsupervised machine learning techniques. The goal is to group customers into distinct clusters based on demographic and spending behavior so that marketing strategies can be tailored for each segment.

Key Objectives:
Understand customer demographics and spending habits.
Apply clustering algorithms to identify distinct customer groups.
Provide actionable insights for targeted marketing.

📂 Dataset
Dataset Name: Mall_Customers.csv

Attributes:
CustomerID – Unique ID for each customer
Gender – Male/Female
Age – Age of the customer
Annual Income (k$) – Annual income in thousand dollars
Spending Score (1–100) – Score assigned by the mall based on customer spending behavior and loyalty
Source: Available on Kaggle and other open data repositories.

🛠 Tools & Technologies
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Algorithm: K-Means Clustering (also tried Hierarchical Clustering for comparison)

📊 Exploratory Data Analysis (EDA)
The EDA phase includes:
Checking missing values and data types
Gender distribution analysis
Age distribution visualization
Annual income & spending score patterns
Relationship between features using scatter plots

⚙️ Methodology
Data Preprocessing
Removed unnecessary columns (CustomerID for clustering)
Handled categorical variables (Gender → numeric encoding)
Feature scaling (if required)
Determining Optimal Clusters
Used Elbow Method and Silhouette Score to decide the best number of clusters.
Model Training
Applied K-Means Clustering on selected features.
Visualized clusters with color-coded scatter plots.
Insights & Recommendations
Identified distinct customer segments (e.g., high income–high spending, low income–low spending, etc.)

📈 Results
Found optimal clusters (e.g., 5 clusters based on spending habits and income)
Clear separation between customer groups, aiding in targeted marketing.

📷 Visualizations
Age distribution
Income vs. Spending score scatter plots
Cluster visualization after applying K-Means

🚀 How to Run
Clone the repository:
git clone https://github.com/yourusername/mall-customer-segmentation.git
Navigate to the project folder:
cd mall-customer-segmentation


Install dependencies:
pip install -r requirements.txt
Run the Jupyter Notebook:
jupyter notebook

📌 Future Improvements
Implement other clustering techniques (DBSCAN, Gaussian Mixture Models)
Add more customer features (e.g., purchase history, location)
Build an interactive dashboard for segmentation insights
