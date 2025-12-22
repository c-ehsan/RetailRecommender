# 🛍️ Smart Recommender System

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-orange.svg)](https://streamlit.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🌟 English Version

### ⚠️ Important Notice
> The dataset used in this project is **very large**, so the Streamlit app **may run slowly** at times.  
> Please be **patient** while it loads and processes the data. Thank you! ⏳

### 🔹 Project Overview
This is a **Smart Recommender System** for retail customers.  
It combines **RFM Analysis (Recency, Frequency, Monetary)** with **Collaborative Filtering** to provide **personalized product recommendations** based on customer purchase behavior.

The system includes:
- Interactive **Streamlit web interface**
- **Data visualization** (PCA projection of clusters & RFM boxplots)
- **RFM segmentation** and **KMeans clustering**
- **Top product recommendations** using collaborative filtering

---

### 🔹 Features
| Feature | Description |
|---------|-------------|
| Data Cleaning & Preprocessing | Handle missing values, negative quantities/prices, duplicates |
| Feature Engineering | Add Total_Price, Year, Month, Day, WeekDay |
| RFM Calculation & Segmentation | Assign R, F, M scores and RFM score |
| Clustering | KMeans clustering of customers |
| Visualization | PCA plot & Boxplots of Recency, Frequency, Monetary |
| Recommendation | Personalized product recommendation via Collaborative Filtering |
| Streamlit Interface | Interactive tables & recommendation cards |

---

### 🔹 Installation

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd <your-repo-folder>
