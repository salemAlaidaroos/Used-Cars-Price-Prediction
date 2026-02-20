#  Used Cars Price Prediction: EDA & Preprocessing

This repository contains a comprehensive **Exploratory Data Analysis (EDA)** and **Data Preprocessing** pipeline for predicting used car prices based on the popular Craigslist dataset. The focus of this project is to clean, analyze, and prepare messy, real-world tabular data for future Machine Learning modeling.

---

##  Project Overview
Real-world data is rarely ready for algorithms. This notebook addresses the common challenges of raw data, taking a dataset of **426,880 vehicle listings with 26 features** and transforming it into a clean, model-ready format.

### **Key Objectives Achieved:**
* **Automated Data Loading:** Integration with `kagglehub` to directly download the `austinreese/craigslist-cars` dataset.
* **Missing Value Imputation:** Handled features with severe missing data (e.g., dropping empty columns like `county` and analyzing `size` which had 72% missing values).
* **Outlier Detection & Removal:** Investigated and resolved extreme anomalies in the dataset, such as vehicle prices recorded up to $3.7 Billion and impossible odometer readings (up to 10M miles).
* **Statistical Summary:** Generated descriptive statistics to understand the distribution of manufacturing years (1900-2022) and pricing logic.

---

##  Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib
* **Machine Learning Tools:** Scikit-learn (for future predictive modeling phases)
* **API Integration:** Kagglehub for dataset acquisition

---

##  How to Use

### 1. Prerequisites
Ensure you have Python installed along with the required Data Science packages:
```bash
pip install pandas numpy matplotlib scikit-learn kagglehub
```

### 2. Running the Notebook
1. Clone the repository and navigate to the project directory.
2. Open the Jupyter Notebook: `Used_Cars_EDA_Preprocessing.ipynb`.
3. The first cell will automatically download the required CSV dataset from Kaggle using your API credentials.
4. Run the cells sequentially to observe the data transformation from raw to clean.

---

### Author
- **Salem Zain Alaidaroos**
- Computer Science Student
- AI and Software Engineering Enthusiast
