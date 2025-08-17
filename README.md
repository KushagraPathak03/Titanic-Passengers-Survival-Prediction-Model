# 🚢 Task 2 – Data Cleaning, EDA, Preprocessing, Feature Engineering, Model Training, Model Evaluation | Data Science Internship @ Prodigy InfoTech
This project is part of **Task 2** of my Data Science Internship.  
It involves **data cleaning, exploratory data analysis (EDA), model training, and evaluation** to predict passenger survival on the Titanic using **Logistic Regression**.

---

## 📌 Project Overview
The Titanic dataset is one of the most famous datasets in the data science world.  
Our goal is to:
1. **Explore** the data and understand relationships between features.
2. **Clean & preprocess** the dataset (handle missing values, encode categorical variables, etc.).
3. **Train** a Logistic Regression model to predict survival.
4. **Evaluate** model performance using various metrics.

---

## 📂 Dataset
Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- Key columns:
  - `PassengerID` - Passenger ID
  - `Pclass` - Passenger class
  - `Name` - Nme of the Passenger 
  - `Sex` - Gender
  - `Age` - Age in years
  - `SibSp` - Number of siblings/spouses aboard
  - `Parch` - Number of parents/children aboard
  - `Ticket` - Ticket number
  - `Fare` - Ticket fare
  - `Cabin` -	Cabin number
  - `Embarked` - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
  - `Survived` - Target variable (0 = No, 1 = Yes)
 
---

## 🖥 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
 
---

## 🛠 Steps Performed

### 1️⃣ Data Cleaning & Preprocessing
- Handled **missing values** (`Age`, `Embarked`, `Fare`).
- Converted **categorical variables** (`Sex`, `Embarked`) into numeric using one-hot encoding.
- Applied **feature scaling** using `StandardScaler`.

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized survival distribution by **gender, class, and age groups**.
- Checked correlations between numerical features and survival.
- Plotted histograms, bar plots, and heatmaps.

### 3️⃣ Model Training
- Model used: **Logistic Regression**
- Train-test split: **80-20**
- Feature scaling applied before training.

### 4️⃣ Model Evaluation
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report**
- Comparison of actual vs predicted values.

---

## 📊 Results
- **Accuracy:** ~82%
- Model shows higher survival prediction accuracy for **female passengers** and **1st-class passengers**.
- Misclassifications often occurred for **young males in higher classes** and **elderly passengers**.

---

## 📈 Visualizations
Some of the EDA visualizations included:
- Survival rate by passenger class
- Survival rate by gender
- Age distribution for survivors vs non-survivors
- Heatmap of feature correlations
