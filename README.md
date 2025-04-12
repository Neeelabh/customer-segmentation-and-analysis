## 🛍️ Online Retail Customer Clustering

This project focuses on segmenting customers of an online retail business using unsupervised machine learning techniques. By leveraging **RFM analysis** and **K-Means clustering**, it aims to help businesses better understand customer behavior and personalize marketing strategies.

---

### 📌 Project Overview

The notebook guides you through:

- **Data cleaning**: Handling missing values, filtering invalid transactions.
- **Feature engineering**: Creating RFM (Recency, Frequency, Monetary) features from transactional data.
- **Exploratory Data Analysis**: Visualizing customer behavior and relationships between RFM features.
- **Clustering**: Applying the K-Means algorithm to identify distinct customer segments.
- **Evaluation**: Using the elbow method to determine the optimal number of clusters.
- **Dimensionality reduction**: PCA for 2D cluster visualization.
- **Cluster profiling**: Interpreting the characteristics of each customer group.

---

### 🧰 Tech Stack

- **Python**  
- **Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

### 📊 Key Outputs

- Number of customer segments identified
- Visualizations of clusters and RFM distributions
- Summary of cluster profiles for business insights

---

### 🚀 How to Run Locally

1. Clone this repository  
2. Install the required packages:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook "online retail customer clustering.ipynb"
   ```
4. Run the cells sequentially to view preprocessing, clustering, and analysis

---

### 📎 Notes

- The dataset used is assumed to follow a typical online retail transaction format (InvoiceNo, CustomerID, Quantity, UnitPrice, etc.).
- Suitable for business analysts, data scientists, or marketers looking to explore customer segmentation techniques.

