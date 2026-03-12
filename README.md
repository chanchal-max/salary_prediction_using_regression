# salary_prediction_using_regression
# Salary Prediction Using Multiple Linear Regression

## Overview

This project predicts **average salary** using **Multiple Linear Regression** based on several features from a job dataset.
The model analyzes factors such as company rating, company age, and required technical skills (Python, AWS, Excel) to estimate the salary offered for a job role.

The project is implemented in **Python using Jupyter Notebook** and demonstrates the basic workflow of a **Machine Learning regression model**, including data preprocessing, model training, evaluation, and visualization.

---

## Dataset

The dataset used in this project is **eda_data.csv**.
It contains job-related information such as:

* Job title
* Company rating
* Company age
* Skills required (Python, AWS, Excel)
* Salary estimates
* Location and company information

For this project, the following columns were used:

* `Rating`
* `age`
* `python_yn`
* `aws`
* `excel`
* `avg_salary` (Target variable)

---

## Technologies Used

* **Python**
* **Jupyter Notebook (.ipynb)**
* **Pandas** – Data handling
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning model

---

## Machine Learning Model

The project uses **Multiple Linear Regression**.

### Input Features

* Company Rating
* Company Age
* Python Skill Requirement
* AWS Skill Requirement
* Excel Skill Requirement

### Target

* Average Salary

---

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Select important features
4. Clean and preprocess the data
5. Split dataset into training and testing sets
6. Train the Linear Regression model
7. Predict salary values
8. Evaluate the model using:

   * Mean Squared Error (MSE)
   * R² Score
9. Visualize **Actual vs Predicted Salary**

---

## Visualization

The project includes a scatter plot showing the relationship between:

* **Actual Salary**
* **Predicted Salary**

This helps evaluate how well the regression model performs.

---

## Example Prediction

Example input:

Rating = 4
Age = 20
Python = 1
AWS = 1
Excel = 1

The model predicts the **expected salary** based on these features.

---

## How to Run the Project

1. Clone the repository
2. Install required libraries
3. Open the notebook in Jupyter
4. Run all cells

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

### Run Notebook

Open the file:

```
salary_prediction.ipynb
```

---

## Project Structure

```
Salary-Prediction-Regression/
│
├── eda_data.csv
├── salary_prediction.ipynb
└── README.md
```

---

## Future Improvements

Possible improvements for this project:

* Use more features from the dataset
* Try advanced models (Random Forest, XGBoost)
* Perform feature importance analysis
* Improve prediction accuracy with better preprocessing

---

## Author

Chanchal Kushwah
