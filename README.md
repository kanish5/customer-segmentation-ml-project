# 🧠 Customer Segmentation using K-Means Clustering

This project applies **unsupervised machine learning** to segment customers based on their behavior and demographics. The goal is to help businesses tailor marketing strategies and personalize experiences for different customer groups.

---

## 📊 Overview

- Dataset: [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- Problem Type: Clustering (Unsupervised ML)
- Algorithm: K-Means
- Tools: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 🧰 Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Google Colab**

---

## 🛠️ Features

✅ Data Preprocessing (Label Encoding + Standard Scaling)  
✅ Elbow Method to determine optimal K  
✅ K-Means Clustering (with `n_clusters=5`)  
✅ 3D Visualization of customer segments  
✅ Final CSV of customer segments for business use

---

## 📈 Key Insights

- K-Means effectively grouped customers into 5 behavior-based clusters
- **Spending Score** and **Annual Income** showed the most distinctive patterns
- Helps identify target groups like:
  - High income, low spenders
  - Low income, high spenders
  - Balanced/mid-range customers

---

## 📁 Project Structure
customer-segmentation/
├── data/
│   └── customers.csv
├── images/
│   ├── 2d_clusters.png
│   ├── elbow_method.png
├── notebooks/
│   └── 01_customer_segmentation.ipynb
├── customers_clustered.csv
└── README.md

---

---

## 📸 Visual Samples

### 2D Cluster Plot  
![2D Cluster Plot](images/2d_clusters.png)

### Elbow Method  
![Elbow Method](images/elbow_method.png)

---

## 📦 How to Run

1. Upload the dataset (`customers.csv`) to your project
2. Run the Jupyter/Colab notebook
3. The clustered output is saved to `customers_clustered.csv`

---

## 📌 Future Improvements

- Use PCA or t-SNE for dimensionality reduction
- Build an interactive dashboard with Streamlit
- Apply DBSCAN or Hierarchical clustering for comparison

---

## 🔗 Dataset Source

- [Kaggle – Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## 🤝 Let's Connect

📧 kanishtyagi123@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/kanishtyagi123/)  
🔗 [GitHub](https://github.com/kanish5)
