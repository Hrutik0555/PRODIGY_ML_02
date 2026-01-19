# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project is part of **Task 2 of the Prodigy InfoTech Machine
Learning Internship**.\
The objective of this task is to perform **customer segmentation** using
unsupervised learning techniques.\
By applying clustering algorithms on customer data, we aim to group
customers based on their purchasing behavior and demographic attributes.

The project uses the **Mall Customer Dataset**, which contains customer
details such as age, gender, annual income, and spending score.

------------------------------------------------------------------------

## ✨ Features

-   Exploratory Data Analysis (EDA) on customer dataset\
-   Data preprocessing and feature scaling\
-   Implementation of **K-Means Clustering**\
-   Optimal cluster selection using the **Elbow Method**\
-   Visualization of customer segments\
-   Interpretation of cluster behavior

------------------------------------------------------------------------

## 🚀 Quick Start

### 1️⃣ Clone the Repository

    git clone https://github.com/your-username/customer-segmentation.git
    cd customer-segmentation

### 2️⃣ Install Dependencies

    pip install -r requirements.txt

### 3️⃣ Dataset

Place the dataset file:

    Mall_Customers.csv

inside the `data/` directory.

### 4️⃣ Run the Notebook

    jupyter notebook Task2.ipynb

Or execute the script:

    python src/train.py

------------------------------------------------------------------------

## 📂 Project Structure

    customer-segmentation/
    │
    ├── data/
    │   └── Mall_Customers.csv
    │
    ├── notebooks/
    │   └── Task2.ipynb
    │
    ├── README.md
    ├── requirements.txt
    └── LICENSE

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 3.x\
-   Pandas & NumPy\
-   Scikit-learn\
-   Matplotlib & Seaborn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📊 Model Performance

### 🔹 Elbow Method Result

The Elbow Method was used to determine the optimal number of clusters by
analyzing the Within-Cluster Sum of Squares (WCSS).\
The optimal number of clusters selected: **K = 5**

### 🔹 Cluster Insights

  Cluster     Customer Type Description
  ----------- -----------------------------------
  Cluster 1   High Income - High Spending
  Cluster 2   High Income - Low Spending
  Cluster 3   Low Income - High Spending
  Cluster 4   Low Income - Low Spending
  Cluster 5   Average Income - Average Spending

These segments help businesses target marketing strategies effectively.

------------------------------------------------------------------------

## 🧠 About Prodigy InfoTech Internship

Prodigy InfoTech provides hands-on internships focused on real-world
applications of Machine Learning, Data Science, and Artificial
Intelligence.\
This task strengthens practical skills in:

-   Exploratory Data Analysis\
-   Unsupervised Learning\
-   Clustering Techniques\
-   Business Insight Generation

------------------------------------------------------------------------

## 📜 License

This project is licensed under the MIT License.\
You are free to use, modify, and distribute this project with proper
attribution.

------------------------------------------------------------------------

## 🙏 Acknowledgments

-   Kaggle & public datasets for providing customer data\
-   Scikit-learn development team\
-   Prodigy InfoTech for the internship opportunity\
-   Open-source community for continuous learning resources

------------------------------------------------------------------------

⭐ If you found this project helpful, consider giving the repository a
star!
