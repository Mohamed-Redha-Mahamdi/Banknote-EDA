
# Bank Credit Dataset Analysis

This repository contains a Jupyter Notebook (`main.ipynb`) where we analyze and process the `german.csv` dataset. 
The analysis includes data exploration, preprocessing, and the development of predictive models to evaluate client creditworthiness.

## Dataset

**File:** `german.csv`  
**Description:** The dataset describes the financial and banking details of clients, aiming to determine if a client is "good" or "bad" in terms of loan repayment.  
The dataset includes 1000 examples and 20 variables, comprising 7 numerical (integer) and 13 categorical features.  

**Variables:**  
- Status of the current account  
- Loan duration (in months)  
- Credit history  
- Loan purpose  
- Credit amount  
- Savings account status  
- Employment duration  
- Repayment rate (percentage of disposable income)  
- Personal status and gender  
- Other debtors  
- Current residence duration  
- Property ownership  
- Age (in years)  
- Other installment plans  
- Housing type  
- Number of credits at this bank  
- Occupation  
- Number of dependents  
- Telephone ownership  
- Foreign worker status  

**Source:**  
[German Credit Data](https://raw.githubusercontent.com/jbrownlee/Datasets/master/german.csv)

## Notebook

**File:** `main.ipynb`  
**Description:** The notebook walks through the following steps:
1. **Data Cleaning:** Handling missing or inconsistent data.
2. **Exploratory Data Analysis (EDA):** Understanding the structure and distribution of the dataset through visualizations and summary statistics.
3. **Feature Engineering:** Creating or modifying features to enhance model performance.
4. **Model Development:**
   - Includes machine learning models for predictive analysis.
   - Comparison of model performance using metrics like accuracy, precision, recall, or other relevant measures.
   - Models used include Logistic Regression, Decision Trees, or other classification models (replace with exact models used).
5. **Visualization:** Leveraging plots to depict patterns, trends, and model performance.

## Requirements

To run the notebook, ensure you have the following Python packages installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` 

Install them via pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook to explore the data and evaluate the models.

## Results

The notebook highlights the following:
- Key insights and trends from the dataset.
- Performance of different models used in the analysis.
- Visualizations for better interpretability.

## Contributions

Contributions are welcome!
