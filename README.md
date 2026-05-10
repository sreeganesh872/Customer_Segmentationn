# Customer Segmentation Analysis using Machine Learning

## Project Overview

This project focuses on customer segmentation using machine learning clustering techniques to analyze customer behavior in a retail environment. The main goal of the project is to group customers into meaningful segments based on their annual income, spending score, and age so businesses can better understand customer patterns and improve marketing strategies.

The project uses the Mall Customers dataset and applies multiple unsupervised machine learning algorithms including:

* K-Means Clustering
* Hierarchical Clustering
* Gaussian Mixture Models (GMM)
* DBSCAN

The analysis compares the performance of these algorithms and identifies the best model for customer segmentation.

---

# Objectives

* Understand customer purchasing behavior using data analysis
* Perform Exploratory Data Analysis (EDA) on customer data
* Apply clustering algorithms for customer segmentation
* Compare clustering techniques using evaluation metrics
* Identify meaningful customer groups for business decision-making
* Visualize customer segments using plots and charts

---

# Dataset Information

The dataset used in this project is the Mall Customers dataset.

### Features in the Dataset

| Feature                | Description                       |
| ---------------------- | --------------------------------- |
| CustomerID             | Unique customer identifier        |
| Gender                 | Male or Female                    |
| Age                    | Customer age                      |
| Annual Income (k$)     | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending behavior score  |

### Dataset Size

* Total Records: 200
* Total Features: 5

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

# Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and relationships within the dataset before applying clustering algorithms.

The following visualizations were used:

* Correlation Heatmap
* Pair Plot
* Scatter Plot
* Distribution Plot

### Key Findings

* Annual income and spending score showed a moderate positive relationship.
* Age had a weaker impact on customer spending behavior.
* Distinct customer patterns were visible through scatter plots.
* The dataset was clean and contained no missing values.

---

# Machine Learning Algorithms Used

## 1. K-Means Clustering

K-Means clustering was used to divide customers into groups based on similarity. The Elbow Method was applied to determine the optimal number of clusters.

### Result

* Best number of clusters: 5
* Highest silhouette score among all models
* Produced clear and interpretable customer groups

### Customer Segments Identified

* VIP Customers
* Target Customers
* Impulsive Buyers
* Budget Customers
* Regular Customers

---

## 2. Hierarchical Clustering

Hierarchical clustering was used to analyze hierarchical relationships between customer groups.

### Features

* Uses dendrogram visualization
* Helps understand cluster relationships
* Good for exploratory analysis

---

## 3. Gaussian Mixture Model (GMM)

GMM was used to perform probabilistic clustering.

### Features

* Provides soft clustering
* Customers can belong partially to multiple groups
* Useful for uncertainty-based analysis

---

## 4. DBSCAN

DBSCAN was applied as a density-based clustering algorithm.

### Features

* Detects outliers
* Identifies arbitrary-shaped clusters
* Works well for density-based segmentation

---

# Model Evaluation

The clustering algorithms were compared using silhouette scores and interpretability.

| Algorithm               | Silhouette Score | Interpretation           |
| ----------------------- | ---------------- | ------------------------ |
| K-Means                 | 0.552            | Best performance         |
| Hierarchical Clustering | 0.541            | Good interpretability    |
| GMM                     | 0.518            | Probabilistic clustering |

### Final Observation

K-Means clustering produced the best balance between cluster quality and business interpretability.

---

# Business Applications

The customer segments identified in this project can help businesses in:

* Personalized marketing
* Customer relationship management (CRM)
* Product recommendation systems
* Customer retention strategies
* Targeted promotional campaigns
* Business decision-making

---

# Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Data Visualization
6. Clustering Model Implementation
7. Model Evaluation
8. Result Interpretation
9. Business Insights Generation

---

# Future Improvements

* Add more customer behavior features
* Perform real-time customer segmentation
* Use time-series customer behavior analysis
* Implement ensemble clustering techniques
* Apply explainable AI methods such as SHAP or LIME

---

# Conclusion

This project demonstrates how machine learning can be effectively used for customer segmentation in retail analytics. Among all clustering methods tested, K-Means clustering achieved the best results and provided meaningful customer groups that can support better marketing and business strategies. The project highlights the importance of data-driven decision-making in improving customer engagement and business growth.

---

# How to Run the Project

## Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## Step 2: Open Jupyter Notebook

```bash
jupyter notebook
```

## Step 3: Run the Notebook

Open the project notebook and run all cells sequentially.

---

# Author

Customer Segmentation Analysis Project

Developed using Machine Learning and Data Analytics techniques.
