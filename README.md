# Customer-Purchase-Behavior-Prediction-and-Market-Basket-Analysis-using-Big-Data-Technologies

📊 Customer Purchase Behavior Prediction and Market Basket Analysis
---
📌 Overview  
This project analyzes customer purchase behavior using Instacart’s dataset. It includes market basket analysis (association rules), collaborative filtering (ALS) for product recommendations, and machine learning models for reorder prediction — all implemented using PySpark and Big Data technologies.

📁 Contents
---
- Final_Report.docx – Project report with detailed insights, metrics, and visualizations  
- main_code.py or notebook.ipynb – Python code for data processing, modeling, and analysis

🔧 Technologies Used
---
- **Apache Spark (PySpark)** – Big Data processing  
- **Google Colab** – Development environment  
- **Spark MLlib** – Machine Learning (ALS, Random Forest)  
- **Matplotlib/Seaborn** – Visualizations  
- **FP-Growth Algorithm** – Association Rule Mining  
- **NetworkX + PageRank** – Graph-based product ranking

📊 Key Features
---
- **Top Products Analysis:** Identifies frequently purchased products  
- **Market Basket Analysis:** Discovers popular item combinations
- **Product Recommendation:** ALS-based collaborative filtering  
- **Reorder Prediction:** Classifies likelihood of reordering using Random Forest  
- **Graph-Based Recommendation:**  
  - Constructs a product co-purchase graph (edges for items bought together > 20,000 times)  
  - Applies a weighted, normalized **PageRank algorithm** to rank product importance  
  - Uses **PySpark** for graph construction and **NetworkX** + **Matplotlib** for visualization  
- **User Behavior Insights:** Trends like most orders on which days

📈 Model Performance
---
- ALS AUC: 0.757  
- Reorder Prediction AUC: 0.657  

🗂️ Dataset
---
- **Source:** Instacart Kaggle Dataset  
- **Size:** 3.4M orders, 30M rows, 50K products, 200K users
