# Boston Housing (Machine Learning)

This project explores the *Boston Housing Dataset* to build models that predict the median value of owner‑occupied homes (*MEDV*) in Boston neighborhoods. The dataset includes socioeconomic, environmental, and structural features. It is also widely discussed today due to ethical concerns and embedded racial bias in some of its variables.

A detailed discussion of the dataset and its limitations can be found here:  
https://fairlearn.org/main/user_guide/datasets/boston_housing_data.html#footcite-carlisle2019racist

---

## Objectives and Methodology

The workflow follows a standard machine learning pipeline:

- **Exploratory Data Analysis (EDA)**  
  Distribution analysis, correlation structure, outlier detection, and examination of sensitive or problematic variables.

- **Data Cleaning and Preprocessing**  
  Handling outliers, feature scaling, transformations.

- **Model Development**  
  Training models.
  
- **Model Evaluation**  
  Metrics including RMSE, MAPE, and R² to assess predictive performance.

- **Results and Interpretation**  
  Feature importance, model insights, and discussion of dataset bias and fairness considerations.

---

## Dataset Description

The Boston Housing dataset contains 506 observations and features such as:

- **CRIM** — Per‑capita crime rate by town  
- **RM** — Average number of rooms per dwelling  
- **NOX** — Nitric oxide concentration (pollution)  
- **DIS** — Weighted distance to employment centers  
- **LSTAT** — Percentage of lower‑status population  
- **MEDV** — Median value of owner‑occupied homes (target variable)

Some versions of the dataset also includes the variable **B**, which encodes the proportion of Black residents using a problematic formula. This has led to the dataset being deprecated in scikit‑learn and used today primarily for fairness and bias analysis.

---

## </> Tech Stack

- **Python**: pandas, numpy, scikit‑learn, statsmodels 
- **Jupyter Notebooks**  
- **Visualization**: Matplotlib, Seaborn  
- **Version Control**: GitHub  
