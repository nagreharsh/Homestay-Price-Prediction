# 🏠 Homestay Price Prediction (End‑to‑End Project)

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](End%20to%20End%20Project%20%281%29%20%281%29.ipynb)  
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)]  
[![Libraries](https://img.shields.io/badge/Pandas–NumPy–Matplotlib–scikit--learn-lightgrey)]  

An end‑to‑end regression pipeline to predict residential homestay prices using Airbnb data. The notebook walks through data ingestion, cleaning, exploratory analysis, outlier treatment, and builds a Linear Regression model for price prediction.

---

## 📋 Table of Contents

- [🔍 Project Objective](#-project-objective)  
- [🗄️ Dataset](#️-dataset)  
- [🛠️ Tech Stack & Libraries](#️-tech-stack--libraries)  
- [📂 Repository Structure](#-repository-structure)  
- [⚙️ Installation & Setup](#️-installation--setup)  
- [🚀 Usage](#-usage)  
- [📈 EDA & Modeling Workflow](#-eda--modeling-workflow)  
- [🎯 Results & Evaluation](#-results--evaluation)  
- [💡 Future Improvements](#-future-improvements)  
- [🤝 Contributing](#-contributing)  
- [📄 License](#-license)  
- [✉️ Contact](#️-contact)  

---

## 🔍 Project Objective

> Build a robust regression model to predict homestay prices of residential properties using Airbnb listings.

Key goals:

1. Ingest and clean raw Airbnb data  
2. Handle missing values and outliers  
3. Explore feature distributions and correlations  
4. Train & evaluate a Linear Regression model  
5. Compare performance with different outlier‐treatment strategies  

---

## 🗄️ Dataset

- **File:** `Air_BNB.xlsx`  
- **Size:** ~ [your dataset size]  
- **Columns include:**  
  - `price` (target)  
  - `bedrooms`, `bathrooms`, `accommodates`, `minimum_nights`  
  - `number_of_reviews`, `reviews_per_month`  
  - `latitude`, `longitude`, `neighbourhood`  
- **Source:** Public Airbnb snapshot (anonymized)

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3.7+  
- **Notebooks:** Jupyter  
- **Data Manipulation:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Modeling:** scikit‑learn  
- **Environment Management:** `venv` or `conda`

---

## 📂 Repository Structure

📦 homestay-price-prediction
┣ 📜 End to End Project (1) (1).ipynb # Main analysis & modeling notebook
┣ 📜 Air_BNB.xlsx # Raw data file
┣ 📜 requirements.txt # Python dependencies
┣ 📜 README.md # Project overview
┗ 📜 LICENSE # License information


## ⚙️ Installation & Setup

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/homestay-price-prediction.git
   cd homestay-price-prediction

2. **Create & activate virtual environment**
   python3 -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate

3. **Install dependencies**
   pip install -r requirements.txt

##🚀 Usage
1. **Launch Jupyter Notebook**
    jupyter notebook
2. **Open Homestay Price Pridiction.ipynb**

3. **Run all cells to reproduce the data cleaning, EDA, and Linear Regression modeling steps.**

##📈 EDA & Modeling Workflow
Import Data

Null Value Treatment

Outlier Detection & Treatment

Mean-based vs. median-based capping

Feature Distribution Analysis

Train–Test Split

Linear Regression Model

##🎯 Results & Evaluation
Baseline (no outlier treatment):

MSE: <value>

R²: <value>

Mean-based Outlier Treatment:

MSE: <value>

R²: <value>

Median-based Outlier Treatment:

MSE: <value>

R²: <value>

See the notebook for full metrics, residual plots, and visualizations.
