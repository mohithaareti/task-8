# task-8
# K-Means Clustering on Mall Customers Dataset  

## 🔹 Objective  
The goal is to group mall customers into different clusters (segments) based on their **Annual Income** and **Spending Score**.  
This helps businesses understand customer types and plan marketing strategies.  

---

## 🔹 Steps Performed  

### 1. Load Dataset  
- Used the `Mall_Customers.csv` dataset.  
- Selected features:  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`  

### 2. Fit K-Means  
- Applied **K-Means clustering** (initially with `K=5`).  
- Each customer is assigned a cluster label.  

### 3. Elbow Method  
- Plotted the **inertia (within-cluster sum of squares)** for K = 1 to 10.  
- The “elbow point” in the graph suggests the best K (number of clusters).  

### 4. Visualize Clusters  
- Plotted clusters in 2D using **Annual Income vs Spending Score**.  
- Each color represents a customer segment.  
- Also used **PCA**  for dimensionality reduction if we had more features.  

### 5. Evaluate with Silhouette Score  
- Calculated the **Silhouette Score** (ranges from -1 to 1).  
- Higher values (closer to 1) indicate **better-defined clusters**.  

---

## 🔹 Tools Used  
- **Pandas** → Load and handle data  
- **Matplotlib** → Visualization  
- **Scikit-learn** → K-Means, PCA, Silhouette Score  
