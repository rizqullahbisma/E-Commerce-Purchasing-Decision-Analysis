# 🛒 E-Commerce Overview & Purchasing Decision Analysis

## 📌 Project Overview
This repository contains an end-to-end analysis of an e-commerce dataset, focusing on **user behavior**, **session patterns**, and **factors influencing purchasing decisions**.  
The goal is to understand how users interact with the platform and what leads to conversions (purchases).

This analysis is designed as a **portfolio project** demonstrating data cleaning, exploratory data analysis (EDA), and business insight generation.

---

## 📂 Repository Structure


├── data/
│ ├── raw/ # Original datasets
│ └── processed/ # Cleaned & transformed data
│
├── notebooks/
│ └── analysis.ipynb # Main analysis notebook
│
├── src/
│ ├── data_cleaning.py # Scripts for cleaning raw data
│ ├── feature_engineering.py
│ └── visualization.py
│
├── reports/
│ ├── figures/ # Saved plots
│ └── summary.pdf # Optional report
│
├── README.md
└── requirements.txt


---

## 🧠 Key Questions Answered

1. **How do users navigate through the platform?**  
   - Page views  
   - Add-to-cart behavior  
   - Session duration  

2. **What factors influence conversion?**  
   - Price sensitivity  
   - Category comparison  
   - Time-to-purchase behavior  

3. **Which product categories require longer decision-making?**  
   - Example: electronics vs fashion  

4. **Which user segments have the highest likelihood to purchase?**

---

## 📊 Main Insights (From the Notebook)

- Users who spend **longer time in a session** tend to be comparing products.
- High-ticket items result in **slower add-to-cart and purchase times**.
- Categories such as **computers/electronics** show longer decision times.
- Users who add multiple products to cart in the same session have a **higher purchase probability**.

---
