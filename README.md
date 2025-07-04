 Task 8: Clustering with K-Means

This task is part of the AI & ML Internship program and focuses on applying **unsupervised learning** using the **K-Means Clustering** algorithm on the **Iris dataset**.

 Objective
To perform clustering on unlabeled data and evaluate the performance of the model using visualization and silhouette score.

Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Dataset Used
**Iris Dataset** from `sklearn.datasets`.  
Features include:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Task Workflow

1. **Load the Dataset**  
   Loaded the Iris dataset using `sklearn.datasets.load_iris()`.

2. **Data Preprocessing**  
   Extracted relevant numerical features for clustering.

3. **Elbow Method**  
   Applied the Elbow Method to determine the optimal number of clusters (`K`). Plotted inertia vs number of clusters.

4. **K-Means Clustering**  
   Performed K-Means clustering with the selected `K=3`. Assigned cluster labels to data points.

5. **PCA for 2D Visualization**  
   Applied Principal Component Analysis (PCA) to reduce the data to 2 dimensions for visualization.

6. **Cluster Visualization**  
   Used scatter plot (with Seaborn) to color-code clusters in 2D PCA space.

7. **Evaluation with Silhouette Score**  
   Evaluated the clustering quality using the **Silhouette Score**.

 Results
- **Optimal K found** using Elbow method: **3**
- **Silhouette Score**: _Approximately 0.55_ (indicates moderate cluster separation)
- **Cluster plot** clearly shows 3 groups using PCA-based visualization

 Files in this Repository
- `task8_kmeans_iris.ipynb` – Code implementation
- `README.md` – Description of the task and outcomes

 **Note**: All libraries used are open-source and the dataset is publicly available. No paid tools were used.
