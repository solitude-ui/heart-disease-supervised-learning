# Heart Disease – Supervised Learning

## Overview

This project is part of **Intermediate Assessment – 2: Supervised Learning**. The project uses a Heart Disease dataset to perform both **classification** and **regression** tasks using machine learning techniques.

The main objective is to explore the dataset, preprocess the data, train multiple supervised learning models, evaluate their performance, and identify the best-performing model for each task.

## Dataset

The dataset used in this project is `heart_disease.csv`.

It contains information about individuals such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- Oldpeak
- Slope
- Number of major vessels
- Thalassemia
- Target

## Tasks Performed

### 1. Exploratory Data Analysis

The dataset is explored to identify:

- Missing values
- Data types
- Summary statistics
- Numerical feature distributions
- Potential outliers
- Distribution of categorical variables

### 2. Data Preprocessing

The following preprocessing techniques are applied where required:

- Missing value handling
- Outlier detection and handling
- Categorical variable encoding
- Feature scaling using `StandardScaler`
- Train-test splitting

### 3. Regression

The regression task predicts **serum cholesterol** using the remaining features.

The following models are trained:

- Linear Regression
- Support Vector Machine (SVM)
- Random Forest Regressor

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### 4. Classification

The classification task predicts whether an individual has heart disease.

**Target:**
- `1` – Heart disease present
- `0` – Heart disease absent

The following models are trained:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

### 5. Model Comparison

The performance of all regression and classification models is summarized in tables.

The best-performing model in each category is selected based on the appropriate evaluation metric.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
heart-disease-supervised-learning/
│
├── heart_disease.csv
├── Heart_Disease_Supervised_Learning.ipynb
└── README.md
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/heart-disease-supervised-learning.git
```

2. Navigate to the project directory:

```bash
cd heart-disease-supervised-learning
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open:

```text
Heart_Disease_Supervised_Learning.ipynb
```

6. Run the notebook cells sequentially.

## Conclusion

This project demonstrates the complete supervised machine learning workflow, starting from **EDA and data preprocessing** and progressing to **model training, evaluation, and comparison** for both regression and classification problems.

The final results are used to determine the best-performing regression and classification models based on their respective evaluation metrics.

## Author

**Adil Niham**

*Intermediate Assessment – 2 | Supervised Learning*
