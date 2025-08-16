# Customer Segmentation using K-Means Clustering  

## 📌 Overview  
This project is part of my **AI & ML Internship (Task 8)** where I implemented **K-Means Clustering** for **Customer Segmentation**.  
The goal is to group mall customers into different segments based on their **Annual Income** and **Spending Score**, so businesses can understand their customers better and make data-driven decisions.  

---

## 📂 Dataset  
- **Mall_Customers.csv**  
- Features used:  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`  

---

## 🧑‍💻 Steps Followed  
1. **Load and Visualize Dataset**  
   - Scatter plots to understand customer distribution.  

2. **Elbow Method**  
   - Used to determine the optimal number of clusters (**K=5**).  

3. **Fit K-Means Algorithm**  
   - Assigned each customer to one of the 5 clusters.  

4. **Cluster Visualization**  
   - Visualized customer segments with different colors.  
   - Cluster centers shown with black "X".  

5. **Evaluation**  
   - Calculated **Silhouette Score** to measure clustering quality.  

---

## 📊 Results (Customer Segments)  
The K-Means algorithm grouped customers into **5 clusters**:  

- **Cluster 0:** High Income – High Spending (*Premium Customers*)  
- **Cluster 1:** Low Income – High Spending (*Budget Shoppers*)  
- **Cluster 2:** High Income – Low Spending (*Careful Spenders*)  
- **Cluster 3:** Low Income – Low Spending (*Less Engaged Customers*)  
- **Cluster 4:** Medium Income – Medium Spending (*Average Customers*)  

---

## ⚙️ Technologies Used  
- Python  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  

---

## 📌 What I Learned  
- Basics of **unsupervised learning**  
- How **K-Means clustering** works  
- Using **Elbow Method** & **Silhouette Score** for evaluation  
- Practical application of clustering for **Customer Segmentation**  

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   https://github.com/adityyaaa-01/Internship-Task-8.git
