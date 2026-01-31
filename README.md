# 🍽 Food Delivery Data Integration & Analysis

## 📌 Project Overview
This project demonstrates a real-world data engineering and analytics workflow by
integrating data from multiple sources and formats into a single analytical dataset.

## 📂 Data Sources
- orders.csv – Transactional order data
- users.json – User master data
- restaurants.sql – Restaurant master data (SQL)

## 🔗 Data Integration Logic
- orders.user_id → users.user_id
- orders.restaurant_id → restaurants.restaurant_id
- Join Type: LEFT JOIN (to retain all orders)

## 📁 Final Output
- total_food_dataset.csv  
This file acts as the **single source of truth** for all analysis and questions.

## 📊 Analysis Performed
- Order trends over time
- User behavior analysis
- City-wise and cuisine-wise performance
- Gold vs Regular membership impact
- Revenue distribution and seasonality

## 🛠 Tech Stack
- Python
- Pandas
- SQLite
- Jupyter Notebook

## 🚀 How to Run
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the notebook inside the `notebooks/` folder

## 🏆 Key Learning Outcomes
- Multi-format data handling (CSV, JSON, SQL)
- Real-world joins and data modeling
- Business-driven data analysis
