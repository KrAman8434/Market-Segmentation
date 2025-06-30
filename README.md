# 🎯 Market Segmentation Using Clustering

This project uses unsupervised learning (KMeans Clustering) to segment customers based on their spending behavior. The goal is to help businesses identify distinct customer groups for targeted marketing strategies.

---

## 📌 Problem Statement

Businesses need to understand their customers to tailor marketing campaigns, product recommendations, and sales strategies. This project applies **market segmentation** using **KMeans clustering** to group similar customers based on key features like income and spending score.

---

## 📂 Dataset

- **File**: `customers.csv`
- **Source**: Simulated customer data for a retail store
---

## 🧠 Objectives

- Perform **Exploratory Data Analysis (EDA)** on customer demographics and spending patterns
- Use **KMeans clustering** to identify natural customer segments
- Visualize and interpret clusters for business decisions

---

## 🔧 Tools & Technologies

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `sklearn` for clustering and preprocessing
- **Environment**: Jupyter Notebook

---

## 📊 EDA Highlights

- Distribution of gender, age, income, and spending score
- Relationships between variables (e.g., Income vs. Spending)
- Outlier and skew detection

---

## 🤖 Clustering Process

1. **Data Preprocessing**:
   - Removed `CustomerID` as it doesn’t contribute to clustering
   - Scaled relevant features using StandardScaler

2. **Choosing Number of Clusters**:
   - Used **Elbow Method** to determine optimal `k`

3. **Model Training**:
   - Trained **KMeans** on selected features

4. **Visualization**:
   - Plotted clusters using 2D and 3D scatter plots
   - Cluster interpretation (e.g., high-income low spenders)

---

## 🧩 Results

- Segmented customers into distinct groups such as:
  - High income, high spenders
  - Low income, high spenders (possibly risky)
  - Young, average income, moderate spenders

- These insights help:
  - Target promotions more effectively
  - Understand customer lifetime value
  - Optimize marketing budget

---

## 📌 Key Learnings

- Gained hands-on experience with unsupervised learning
- Learned to apply clustering in a business context
- Practiced EDA, data cleaning, scaling, and KMeans evaluation

---

## 🚀 Future Improvements

- Use **DBSCAN or Hierarchical Clustering** for comparison
- Apply **PCA** for dimensionality reduction
- Add more features like loyalty score, last purchase date
- Deploy model using **Streamlit** or build a **dashboard**

---

## 📁 How to Run This Project

```bash
1. Clone the repo
2. Install required packages: pip install -r requirements.txt
3. Open `Market_Segmentation.ipynb` in Jupyter Notebook
4. Run all cells to view results
