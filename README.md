# Coder_Roots Assignment

This repository contains solutions to three tasks involving data manipulation, visualization, and predictive modeling. Each task demonstrates specific data science techniques using Python.

---

## Task 1: Data Manipulation and Cleaning

### Objective:
Clean and analyze the `employee_data.csv` dataset.

### Steps:
1. Remove duplicate entries.
2. Handle missing values (fill them with default values or drop the rows).
3. Convert the `JoiningDate` column to a proper datetime format.
4. Filter out employees where the `Status` is "Resigned".
5. Analyze the data:
   - Find the average salary by department.
   - List employees who joined after 2020.

### Code:
Refer to the script `task1_Data Manipulation and Cleaning.ipynb`.

### Outputs:
- Cleaned DataFrame.
- Average salary per department.
- List of employees who joined after 2020.

---

## Task 2: Data Visualization

### Objective:
Explore a public dataset through visualizations.

### Dataset:
Any public dataset can be used (e.g., Titanic dataset).

### Steps:
1. Load the dataset into a Pandas DataFrame.
2. Create four meaningful visualizations using Matplotlib or Seaborn.
   - Examples: Bar plots, histograms, box plots, etc.
3. Generate a correlation heatmap for numerical variables.

### Code:
Refer to the script `task2_data_visualization.py`.

### Outputs:
- Visualizations:
  1. Survival rate by passenger class.
  2. Histogram of passenger ages.
  3. Box plot of fare distribution.
  4. Correlation heatmap.

---

## Task 3: Predictive Modeling (Classification)

### Objective:
Build a classification model to predict the presence of diabetes based on health metrics.

### Dataset:
[Diabetes Prediction Dataset](https://github.com/gurmindero7/test_datasets/blob/main/diabetes_prediction_dataset.csv)

### Steps:
1. **Data Preprocessing**:
   - Replace missing or undefined values.
   - Convert categorical variables to numerical using encoding techniques.
   - Normalize or scale features if necessary.
2. **Model Building**:
   - Split the dataset into training and testing sets.
   - Train two classification models:
     1. Logistic Regression
     2. Decision Tree
3. **Model Evaluation**:
   - Evaluate models using accuracy, precision, recall, and F1 score.

### Code:
Refer to the script `task3_predictive_modeling.py`.

### Outputs:
- Preprocessed dataset.
- Performance metrics for Logistic Regression and Decision Tree models:
  - Accuracy, Precision, Recall, F1 Score.

---

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-science-tasks.git
   cd data-science-tasks
