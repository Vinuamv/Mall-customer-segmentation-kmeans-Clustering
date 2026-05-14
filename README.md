# 🛍️ Customer Segmentation using K-Means Clustering

A machine learning project that applies unsupervised learning techniques to segment retail customers based on purchasing patterns. The project analyzes mall customer data to identify distinct customer groups, enabling data-driven business insights and targeted marketing strategies.

---

## Project Overview

Customer segmentation is a key application of machine learning in retail analytics. This project uses the K-Means clustering algorithm to categorize customers into meaningful groups based on their annual income and spending behavior.

The objective is to understand customer patterns and support strategic business decisions such as personalized promotions, loyalty targeting, and market analysis.

---

## Dataset

Source: [Kaggle Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python?utm_source=chatgpt.com)

The dataset contains 200 customer records with 5 attributes:

| Feature | Description |
|---|---|
| CustomerID | Unique identifier |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Score assigned by mall based on purchasing behavior |

---

## Problem Statement

Retail businesses often serve customers with different purchasing habits. Understanding these groups is important for:

- targeted marketing
- customer retention
- personalized recommendations
- sales strategy optimization

This project clusters customers into similar groups using K-Means.

---

## Methodology

### 1. Data Collection
Dataset imported from Kaggle and loaded into Google Colab.

### 2. Data Preprocessing
- verified null values
- selected relevant features
- normalized data using StandardScaler

### 3. Exploratory Analysis
Basic data inspection performed to understand structure and feature distribution.

### 4. Optimal Cluster Selection
Elbow Method used to identify the best value of K.

### 5. Model Training
K-Means clustering applied to segment customers.

### 6. Visualization
Scatter plots generated to display customer segments and centroids.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Results

The algorithm identified **5 distinct customer clusters**, representing different spending profiles such as:

- high-income high-spending customers
- average spenders
- cautious customers
- low-engagement customers
- premium segment customers

These clusters can be used for strategic retail decision-making.

---

## Project Structure

```text
mall-customer-segmentation-kmeans/
├── Mall_Customer_KMeans_Clustering.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
├── LICENSE
└── images/
```

---

## How to Run

### Clone repository

```bash
git clone https://github.com/yourusername/mall-customer-segmentation-kmeans.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run notebook

Open:

`Mall_Customer_KMeans_Clustering.ipynb`

---

## Future Scope

Possible enhancements:

- PCA dimensionality reduction
- DBSCAN clustering comparison
- Streamlit dashboard
- deployment as web application
- customer recommendation system

---

## Learning Outcomes

This project demonstrates practical understanding of:

- unsupervised learning
- clustering algorithms
- feature scaling
- data visualization
- business analytics

---

## Author

Vinu  
Computer Science Engineering Student  
Focused on machine learning, IoT, and research-driven projects.
