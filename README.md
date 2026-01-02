# Predicting Insurance Claim Amounts

##  Objective
The objective of this project is to estimate medical insurance claim amounts based on personal information using a Linear Regression model.

---

##  Dataset
**Medical Cost Personal Dataset** (Kaggle)

The dataset includes the following features:
- `age` – Age of the individual
- `sex` – Gender of the individual
- `bmi` – Body Mass Index
- `children` – Number of dependents
- `smoker` – Smoking status (yes/no)
- `region` – Residential area
- `charges` – Medical insurance cost (target variable)

 Dataset Link:  
https://www.kaggle.com/datasets/mirichoi0218/insurance

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Loading & Exploration
- Loaded dataset using pandas
- Checked shape, columns, and missing values

### 2. Data Visualization
- Analyzed the impact of:
  - Age vs Insurance Charges
  - BMI vs Insurance Charges
  - Smoking Status vs Insurance Charges
- Used scatter plots and box plots for visualization

### 3. Data Preprocessing
- Converted categorical variables into numerical format using One-Hot Encoding
- Prepared features and target variable

### 4. Train-Test Split
- Split the dataset into:
  - 80% training data
  - 20% testing data

### 5. Regression Modeling
- Trained a **Linear Regression** model to predict insurance charges

### 6. Model Evaluation
- Evaluated model performance using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**

### 7. Feature Correlation Analysis
- Created a correlation heatmap to analyze relationships between features and insurance charges

---

## 📈 Results
- The Linear Regression model provides reasonable predictions for insurance charges
- Smoking status, BMI, and age significantly impact insurance costs
- Error metrics (MAE & RMSE) help evaluate model accuracy

---

## ▶️ How to Run the Project
1. Download the dataset from Kaggle
2. Place `insurance.csv` in the project directory
3. Open the Jupyter Notebook:
