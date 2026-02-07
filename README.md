
# Titanic Dataset: Exploratory Data Analysis (EDA) 🛳️

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

This repository contains a **step-by-step Exploratory Data Analysis (EDA)** of the Titanic dataset.  
It focuses on understanding passenger survival patterns using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 📂 Repository Contents

- `Titanic_EDA.ipynb` — Main notebook with detailed EDA, visualizations, and feature engineering  
- `titanic_dataset.csv` — Titanic dataset used in the notebook

---

## 🚀 Features

- Data Overview: shape, columns, missing values  
- Univariate Analysis: Age, Fare, SibSp, Parch, Sex, Pclass, Embarked  
- Bivariate Analysis: Survival by Sex, Pclass, Embarked, FamilySize, IsAlone  
- Multivariate Analysis: Correlation heatmaps  
- Feature Engineering: FamilySize, IsAlone, Title extraction  
- Clear and visually appealing **Matplotlib & Seaborn plots**

---

## ⚡ Quick Start

1. Clone the repository:

```bash
git clone <YOUR_REPO_URL>
cd <REPO_FOLDER>
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook:

```bash
jupyter notebook Titanic_EDA.ipynb
```

4. Run all cells and explore the insights.

---

## 🔑 Key Insights

- **Sex**, **Pclass**, and **Age** are major factors affecting survival.  
- Traveling **alone vs. with family** significantly affects survival rates.  
- Titles extracted from names (e.g., Miss, Master, Rare) provide additional survival context.

---

## 📚 Dataset

- Kaggle Titanic Dataset: [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)

---

*This project focuses purely on EDA and data insights. Predictive modeling is not included in this notebook.*
