# 🚢 Titanic Survival Analysis: Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the famous Titanic dataset. The goal is to uncover patterns and identify the key factors that influenced the survival rates of passengers using statistical analysis and data visualization techniques.

This analysis focuses on data cleaning, handling missing values, and visualizing correlations between variables such as **Age**, **Gender**, and **Socio-Economic Class**.

## 📊 Key Findings
Based on the analysis, the following patterns were observed:
* **Gender Priority:** Female passengers had a significantly higher survival rate (~74%) compared to males (~18%), confirming the "Women and children first" protocol.
* **Socio-Economic Impact:** Passengers in **1st Class** were more likely to survive than those in 3rd Class, indicating a strong correlation between social status and survival.
* **Family Size:** Passengers traveling with small families (1-3 members) had better survival chances than those traveling alone or with large families.
* **Data Integrity:** The dataset contained significant missing values in the `Cabin` column (dropped) and `Age` column (imputed with mean).

## 🛠️ Technologies Used
* **Programming Language:** Python 3.13
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook / VS Code

## 📂 Project Structure
```bash
├── .gitignore               # Files to be ignored by Git
├── README.md                # Project documentation
├── Titanic-Dataset.csv      # Raw dataset
├── ilk_eda_projem.ipynb     # Main analysis notebook (Jupyter)
└── requirements.txt         # List of dependencies
```


How to Run the Project
Follow these steps to set up and run the project locally:

1. Clone the Repository

```bash
git clone [https://github.com/Lostraci/titanic-eda-analysis.git](https://github.com/Lostraci/titanic-eda-analysis.git)
cd titanic-eda-analysis
```

2. Create a Virtual Environment (Optional but Recommended)
```bash

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
venv\Scripts\activate
```
3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Run the Notebook
```bash
Open the .ipynb file in VS Code or launch Jupyter Notebook:

jupyter notebook ilk_eda_projem.ipynb
```