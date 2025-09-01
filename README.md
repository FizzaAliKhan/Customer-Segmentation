🛍️ Customer Segmentation using KMeans
📌 Project Overview

This project focuses on customer segmentation using machine learning techniques. The goal is to group customers into distinct segments based on their purchasing behavior, demographics, and spending patterns. Businesses can leverage this analysis to:

Understand customer behavior

Personalize marketing strategies

Improve customer retention and sales

We applied KMeans clustering to identify hidden patterns and generate meaningful customer groups.

⚙️ Tech Stack

Python 🐍

Pandas, NumPy – Data preprocessing & analysis

Scikit-learn – Machine Learning (KMeans, scaling, PCA)

Matplotlib – Visualization

Jupyter Notebook / Colab – Development environment

🗂️ Dataset

The dataset contains customer demographic and spending details, including:

Gender

Age

Annual Income

Spending Score

Profession

Work Experience

Family Size

(You can replace this section with a link if your dataset is public)

🧩 Methodology

Data Preprocessing

Removed irrelevant columns (CustomerID)

Encoded categorical variables (Gender, Profession)

Standardized numerical values for fair clustering

Finding Optimal Clusters

Used Elbow Method (Inertia)

Verified with Silhouette Score

Clustering with KMeans

Applied KMeans with optimal k

Assigned customers to different clusters

Visualization

Reduced data dimensions using PCA

Plotted customer clusters in 2D space
