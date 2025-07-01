# 🛍️ Customer Segmentation Using K-Means Clustering

Hey there! 👋  
This is a simple and practical machine learning project where I tried to segment customers based on their purchasing behavior using unsupervised learning. I used **K-Means Clustering** to group similar customers together so businesses can understand them better and take smarter decisions like targeted marketing or loyalty rewards.

The dataset I used is from **Online Retail II**, which contains transactional data for an e-commerce company based in the UK. It’s a popular dataset on Kaggle and perfect for hands-on learning.

---

## 🔍 What This Project Is About

The main goal was to:
- Group customers based on how recently and frequently they purchase, and how much money they spend.
- Understand different types of customers like loyal ones, occasional buyers, and those who might not return.
- Visualize and analyze these customer segments to help businesses make better decisions.

This technique is very useful in real-life marketing strategies. Think of how Netflix or Amazon personalizes what you see — customer segmentation is the first step behind that!

---

## 📊 Dataset Details

- **Name**: Online Retail II
- **Source**: [Kaggle](https://www.kaggle.com/datasets/mmartin/online-retail-ii-data-set-from-ml-repository)
- **Time Period**: 2009 to 2011
- **Main Columns Used**: Invoice Date, Quantity, Price, Customer ID, Country

---

## 🧰 Tools & Libraries Used

- Python 🐍  
- Pandas, NumPy – for data handling  
- Matplotlib, Seaborn – for visualizations  
- Scikit-learn – for machine learning (KMeans, scaling)  
- Jupyter Notebook – for writing and running the code

---

## 🔧 Steps I Followed

### 1. Data Cleaning
- Removed rows with missing Customer IDs
- Filtered out canceled transactions (negative quantity)
- Focused on customers from the UK to keep things consistent (optional step)

### 2. Feature Engineering: RFM Analysis
- **Recency**: How recently a customer made a purchase
- **Frequency**: How often they purchase
- **Monetary**: How much they spent

### 3. Normalization
- Used Min-Max Scaling to bring values to the same scale for better clustering

### 4. Clustering
- Used the **Elbow Method** to find the optimal number of clusters
- Applied **K-Means Clustering** on the scaled RFM values

### 5. Visualization & Interpretation
- Visualized the clusters using scatter plots
- Analyzed each group based on spending habits and frequency

---

## 🎯 Results in Simple Words

After clustering, I got groups like:
- 🟢 **Loyal customers**: They buy often, spend well, and recently shopped.
- 🟡 **Potential churners**: They used to spend a lot but haven’t bought anything recently.
- 🔴 **Low-value customers**: They rarely buy and don’t spend much.

With this kind of segmentation, a business can:
- Give discounts to loyal customers
- Win back lost ones with special offers
- Stop wasting marketing budget on non-engaged users

---




