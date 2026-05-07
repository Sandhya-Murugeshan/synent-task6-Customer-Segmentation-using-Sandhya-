# Customer Segmentation using K-Means Clustering

##  Project Overview
This project performs customer segmentation using the Mall Customer Dataset.  
The goal is to group customers based on their purchasing behavior using the K-Means clustering algorithm.

Customer segmentation helps businesses understand customer groups and create better marketing strategies.

---

##  Objective
- Perform data preprocessing
- Apply K-Means clustering
- Identify customer groups
- Visualize customer segments
- Generate business insights

---

##  Dataset
Dataset Used: Mall Customer Dataset

Features Used:
- Annual Income (k$)
- Spending Score (1-100)

---

##  Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

---

##  Steps Performed

### 1. Import Libraries
Imported required Python libraries for data analysis, visualization, and clustering.

### 2. Load Dataset
Loaded the Mall Customer dataset using Pandas.

### 3. Data Preprocessing
Selected important features and normalized the data using StandardScaler.

### 4. Find Optimal Clusters
Used the Elbow Method and WCSS (Within Cluster Sum of Squares) to determine the optimal number of clusters.

### 5. Apply K-Means Clustering
Applied the K-Means algorithm to group customers into clusters.

### 6. Visualize Clusters
Visualized customer segments using a scatter plot.

### 7. Generate Insights
Analyzed customer groups such as:
- High income – High spending customers
- Low income – Low spending customers
- Potential customers
- Average customers

---

##  Output
- Customer segmentation visualization and behavior insights
-<img width="1920" height="1080" alt="Screenshot 2026-05-07 092106" src="https://github.com/user-attachments/assets/82268c40-8c21-41a8-b515-3ea294f49b84" />
 <img width="1920" height="1080" alt="Screenshot 2026-05-07 092115" src="https://github.com/user-attachments/assets/6b967700-f93a-4782-ad17-ca1e53d4a107" />
- Cluster-based grouping
- <img width="1920" height="1080" alt="Screenshot 2026-05-07 092122" src="https://github.com/user-attachments/assets/9a86d3c3-fd3b-4c4f-a853-bb4abc4a1cc4" />

---

##  Key Insights
- Premium customers were identified based on high income and high spending.
- Budget customers showed low spending behavior.
- Some customers had high income but low spending, indicating marketing opportunities.
- Customer segmentation helps improve targeted marketing strategies.

---

##  Conclusion
K-Means clustering successfully grouped customers into meaningful segments based on their income and spending behavior.  
This project demonstrates how unsupervised machine learning can help businesses better understand customer patterns.

---
