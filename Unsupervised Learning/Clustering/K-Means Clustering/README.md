# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project implements the K-Means Clustering algorithm, an unsupervised machine learning technique used to group similar data points into clusters.  

The model analyzes mall customer data and segments customers based on their annual income and spending score.

---

## 🎯 Objective
The main objective of this project is to:
- Understand unsupervised learning
- Implement the K-Means Clustering algorithm
- Visualize customer groups
- Identify different customer segments for business analysis


### Dataset Features
| Feature | Description |
|---|---|
| CustomerID | Unique customer ID |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending score |

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## 📈 Project Workflow

### 1. Import Libraries
Imported all required Python libraries for data analysis, visualization, and clustering.

### 2. Load Dataset
Loaded the dataset into a Pandas DataFrame.

### 3. Data Analysis
Performed:
- Dataset inspection
- Statistical analysis
- Null value checking

### 4. Data Visualization
Visualized customer distribution using scatter plots.

### 5. Feature Selection
Selected:
- Annual Income
- Spending Score

for clustering.

### 6. Elbow Method
Used the Elbow Method to determine the optimal number of clusters.

### 7. K-Means Clustering
Trained the K-Means model using the selected number of clusters.

### 8. Cluster Visualization
Visualized the final customer segments and cluster centroids.

---

## 📉 Elbow Method
The Elbow Method was used to identify the optimal value of K by analyzing the Within-Cluster Sum of Squares (WCSS).

Optimal clusters selected:
```python
K = 5
```

---

## 📷 Visualizations

### Customer Distribution
<img src = "https://github.com/sankalpams/Machine-Learning-Algorithms/blob/0468f73f9d89899ea68432d892cacdc7e251f794/Unsupervised%20Learning/Clustering/K-Means%20Clustering/Visuals/Customer%20Distribution.png" height="350">

### Elbow Method Graph
<img src = "https://github.com/sankalpams/Machine-Learning-Algorithms/blob/0468f73f9d89899ea68432d892cacdc7e251f794/Unsupervised%20Learning/Clustering/K-Means%20Clustering/Visuals/Elbow%20Method%20Graph.png" height ="350">

### Final Customer Segments
<img src = "https://github.com/sankalpams/Machine-Learning-Algorithms/blob/0468f73f9d89899ea68432d892cacdc7e251f794/Unsupervised%20Learning/Clustering/K-Means%20Clustering/Visuals/Final%20Customer%20Segments.png" height = "350">

## 🎯 Results
The K-Means model successfully segmented customers into multiple groups based on their spending behavior and annual income.

Some identified customer groups:
- High income, high spending customers
- High income, low spending customers
- Low income, high spending customers
- Average income customers



## 📚 Key Concepts Learned
- Unsupervised Learning
- Clustering
- K-Means Algorithm
- Elbow Method
- Data Visualization
- Customer Segmentation
