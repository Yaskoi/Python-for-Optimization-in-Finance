# 🧠 Python for Optimization in Finance

## 📌 Project Overview
This project aims to apply **data analysis and optimization techniques** to a dataset of **105 anonymized ETFs** (since 2019) in order to:
- Classify ETFs based on **risk, performance, and interrelationships**.
- Identify **connections between ETFs and major asset classes** (regional equities, sovereign bonds, high yield, commodities, and the Dollar Index).
- Detect and interpret the composition of a **Mystery Allocation**, which may be either fixed or dynamically adjusted over time.

The project encourages autonomy, critical thinking, and a rigorous quantitative approach to financial data analysis in Python.

---

## 📊 Dataset Description
The dataset includes:
- **105 anonymized ETFs** with daily historical prices since 2019.  
- **14 benchmark assets** representing major asset classes:
  - Regional Equities  
  - Regional Sovereign Bonds  
  - High-Yield Bonds  
  - Commodities  
  - Dollar Index  
- Two types of *Mystery Allocation*:
  1. **Fixed allocation** — constant throughout the period.  
  2. **Dynamic allocation** — varies infrequently over time.  

---

## 🎯 Objectives
1. Classify ETFs according to **risk exposure** and **performance characteristics**.  
2. Identify **relationships between ETFs and core asset classes**.  
3. Estimate the **composition of the Mystery Allocation** and quantify uncertainty.  
4. Discuss potential **biases, missing assets, or model limitations**.  

---

## 🧩 Methodology
The project allows full methodological freedom.  
Recommended or potential approaches include:
- **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.  
- **Clustering methods** such as K-Means, Hierarchical Clustering, or DBSCAN for ETF classification.  
- **Regression or correlation analysis** to link ETFs with main asset classes.  
- **Portfolio optimization models** (Markowitz, Risk Parity, Shrinkage Covariance).  
- **Hybrid techniques** combining statistical, machine learning, and financial modeling tools.  

Sophistication is not necessarily the key — clarity, interpretability, and relevance are prioritized.

---

## 👥 Authors

Project developed as part of the Python for Optimization in Finance course.
Authors: Yassine Housseine, Louis Monin, Alain Richard Belinga

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/<user>/Python-for-Optimization-in-Finance.git
cd Python-for-Optimization-in-Finance

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
