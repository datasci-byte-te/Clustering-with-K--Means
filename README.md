Mall Customer Segmentation using K-Means Clustering

This project demonstrates the use of unsupervised machine learning techniques for customer segmentation using the K-Means Clustering algorithm. 


## 📌 Objective

To segment customers into distinct clusters based on their age, annual income, and spending score. This helps mall management or marketing teams identify and target key customer groups more effectively.


## ⚙️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (KMeans, StandardScaler, PCA, silhouette_score)


## 📊 Steps Performed

1. Data Loading & Exploration
2. Feature Selection** (`Age`, `Annual Income`, `Spending Score`)
3. Data Standardization using `StandardScaler`
4. Finding Optimal K using the **Elbow Method**
5. Clustering using `KMeans`
6. Evaluation using **Silhouette Score**
7. Dimensionality Reduction using **PCA** (for 2D visualization)
8. Cluster Visualization with color-coded scatter plots


## 📈 Output

- **Elbow Plot** to determine the optimal number of clusters (K)
- **Silhouette Score** to evaluate the clustering quality
- **2D Scatter Plot** of customer clusters using PCA



## 💡 Insights

This clustering model helps in:
- Identifying high-value customers (e.g., high income, high spending)
- Spotting frugal or low-engagement customers
- Designing targeted marketing campaigns based on customer profiles



