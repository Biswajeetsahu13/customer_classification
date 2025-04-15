# customer_classification
# 🧑‍💼 Customer Classification

This project demonstrates how machine learning can be used to segment customers into distinct groups based on demographic and behavioral data. By clustering similar customer profiles, businesses can tailor marketing efforts, improve service delivery, and boost customer engagement.

---

## 📁 Dataset Overview

The dataset used includes customer details with the following features:

| Feature          | Description                                               |
|------------------|-----------------------------------------------------------|
| `Gender`         | Gender of the customer (Male/Female)                      |
| `Age`            | Age of the customer                                       |
| `Annual Income`  | Annual income in thousands of currency units              |
| `Spending Score` | Score between 1 and 100 indicating customer spending behavior |

---

## 🎯 Objective

To classify customers into distinct segments based on their income, age, spending score, and other behavioral traits using **unsupervised machine learning techniques**, particularly **K-Means Clustering**.

---

## 🧠 Methodology

### 1. Data Preprocessing
- Handled missing values (if any)
- Encoded categorical data (`Gender`)
- Scaled numerical features for better model performance

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of age, income, and spending
- Analyzed relationships between different features

### 3. Clustering with K-Means
- Used the **Elbow Method** to determine optimal number of clusters
- Applied **K-Means Clustering** to segment customers
- Visualized resulting clusters in 2D and 3D space

---

## 📊 Results

The K-Means model successfully segmented the customers into groups such as:

- High-income, high-spending customers
- Budget-conscious customers
- Younger vs older demographics with distinct patterns

These clusters can help businesses:
- Develop targeted marketing campaigns
- Personalize product recommendations
- Prioritize customer service efforts

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Clustering and preprocessing

---

## 📁 Project Structure

