# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior.

The segmentation helps businesses understand different customer groups and make better marketing decisions.

---

## 🎯 Objective

* Group customers into different clusters
* Identify patterns in customer spending behavior
* Visualize customer segments

---

## 📊 Dataset

The dataset contains customer information including:

* Annual Income (k$)
* Spending Score (1-100)

---

## ⚙️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn

---

## 🧠 Algorithm Used

* **K-Means Clustering**

---

## 📈 Methodology

### 1. Feature Selection

Selected key features:

* Annual Income
* Spending Score

### 2. Elbow Method

Used to determine the optimal number of clusters (K) by analyzing WCSS values.

### 3. Model Training

Applied K-Means clustering with optimal K value.

### 4. Visualization

* Elbow curve
* Cluster scatter plot with centroids

---

## 📉 Visualizations

### 🔹 Elbow Method

![Elbow Plot](images/elbow_plot.png)

### 🔹 Customer Segments

![Clusters](images/clusters.png)

---

## 📂 Project Structure

```text
customer-segmentation-kmeans/
│
├── Mall_Customers.csv
├── customer_segmentation_kmeans.py
├── requirements.txt
├── images/
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python customer_segmentation_kmeans.py
```

---

## 📌 Results

The model successfully segments customers into distinct groups based on income and spending patterns, helping in targeted marketing strategies.

---

## 🙌 Acknowledgment

This project was completed as part of a **Machine Learning Internship Task (Task 02)**.

---

## 📬 Connect

Feel free to connect with me on LinkedIn for collaboration and opportunities.
