# E-Commerce-Analytics-
# 🛒 E-Commerce Analytics Project

[![View Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://github.com/pa7003/E-Commerce-Analytics-/blob/main/E_Commerce_Analytics_.ipynb)

This project presents a comprehensive end-to-end analysis of e-commerce data using advanced data science and machine learning techniques. From data preprocessing and exploratory data analysis to funnel modeling, A/B testing, uplift modeling, and personalization, this notebook captures a full lifecycle of business intelligence in the online retail domain.

---

## 📁 Repository Contents

- `E_Commerce_Analytics_.ipynb`: The main analysis notebook with code, visuals, and detailed explanations.
- 📊 Charts & Visualizations: Embedded within the notebook, covering KPIs, funnels, cohort trends, uplift, churn models, etc.
- 📂 Data: Dataset imported from Kaggle [Brazilian E-commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

---

## 📌 Key Features & Workflow

### ✅ 1. Advanced Data Cleaning & Preprocessing
- Timestamp conversion and timezone handling
- Feature engineering (e.g., `order_value`, `days_since_last_purchase`)
- Null value treatment and intelligent imputation

### 📊 2. Exploratory Data Analysis (EDA)
- Order volume, revenue trends, and top product categories
- Delivery performance and delays
- Purchase patterns (weekly/monthly trends)

### 🔄 3. Funnel Analysis
- Basic funnel: Browsed → Added to Cart → Purchased → Delivered
- Drop-off analysis and status breakdowns
- Time-series funnel comparisons (weekly/monthly)
- Predictive funnel modeling using classification

### 🧪 4. A/B Testing & Uplift Modeling
- Simulated control vs. treatment segmentation
- Evaluation using Qini and uplift score
- Visual comparisons of A/B test vs. uplift model

### 🧠 5. Customer Analytics
- CLV (Customer Lifetime Value) prediction
- Churn classification model
- Cohort analysis & retention visualization

### 🤖 6. Recommendation & Personalization
- Lift and confidence-based product suggestions
- Segment-based personalization logic

### 🧩 7. Clustering & Segmentation
- RFM modeling
- Customer groups for targeted marketing

### ⏱️ 8. Real-Time Analytics (Simulated)
- Timestamped data simulation
- Stream-ready transformations for live dashboards

---

## 📦 Tech Stack

- **Language**: Python 3.11
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`, `lifetimes`, `uplift`, `xgboost`, etc.
- **Platform**: Jupyter Notebook (Google Colab compatible)
- **Dataset**: Brazilian E-Commerce Dataset (Olist)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/pa7003/E-Commerce-Analytics-.git
   cd E-Commerce-Analytics-
2. Open E_Commerce_Analytics_.ipynb in Jupyter Notebook or Google Colab.

3. Run all cells sequentially or interact with specific sections.
