# SCT_ML_02 - Customer Segmentation Using K-Means Clustering

## SkillCraft Technology Machine Learning Internship

### Task 02: Customer Segmentation

## Project Overview

This project implements the K-Means Clustering algorithm to group customers of a retail store based on their purchasing behavior. Customer segmentation helps businesses understand different customer groups and create targeted marketing strategies.

The model uses customer Annual Income and Spending Score to identify distinct customer segments and visualize them using scatter plots.

---

## Objective

To apply the K-Means Clustering algorithm for customer segmentation and gain insights into customer purchasing patterns.

---

## Dataset

The dataset contains the following features:

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

### Features Used for Clustering

* Annual Income (k$)
* Spending Score (1-100)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* VS Code

---

## Steps Performed

1. Imported required libraries.
2. Loaded and explored the dataset.
3. Selected relevant features.
4. Applied feature scaling.
5. Used the Elbow Method to determine the optimal number of clusters.
6. Applied K-Means Clustering.
7. Visualized customer segments.
8. Analyzed clustering results.

---

## Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Run the Project

```bash
python kmeans.py
```

---

## Output

The algorithm groups customers into different categories such as:

* High Income – High Spending
* High Income – Low Spending
* Low Income – High Spending
* Low Income – Low Spending
* Average Customers

The project generates:

* Elbow Method Graph
* Customer Segmentation Plot
* Cluster Centroids

---

## Project Structure

```text
SCT_ML_02/
│
├── kmeans.py
├── Mall_Customers.csv
└── README.md
```

---

## Learning Outcomes

* Understanding Unsupervised Learning
* K-Means Clustering
* Feature Scaling
* Customer Segmentation
* Data Visualization
* Cluster Analysis

---

## Internship Details

**Company:** SkillCraft Technology

**Domain:** Machine Learning

**Task Code:** SCT_ML_02

**Task:** Customer Segmentation Using K-Means Clustering

---



---

## Acknowledgement

I would like to thank SkillCraft Technology for providing this opportunity to enhance my Machine Learning skills through practical project-based learning.
