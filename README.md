# 🚢 Titanic Survival Prediction using Naive Bayes

This project uses the **Naive Bayes classification algorithm** to predict whether a passenger survived the Titanic disaster based on features like age, gender, and passenger class.

---

## ❓ Why This Project
- The Titanic dataset is one of the most famous datasets for learning **machine learning classification**.  
- It provides real-world data with categorical, numerical, and missing values.  
- The project helps understand how **Naive Bayes** can be applied to solve binary classification problems.  

---

## ⚙️ How It Works
1. **Data Loading** – Load the Titanic dataset (`titanicsurvival.csv`).  
2. **Exploratory Data Analysis (EDA)** – Check dataset size, features, and distribution of survival outcomes.  
3. **Data Preprocessing**  
   - Handle missing values.  
   - Encode categorical variables (e.g., Sex, Embarked).  
   - Split dataset into training and testing sets.  
4. **Model Training** – Apply the **Naive Bayes algorithm** from scikit-learn.  
5. **Prediction** – Predict passenger survival on the test set.  
6. **Evaluation** – Measure accuracy, precision, recall, and confusion matrix.  

---

## 📂 Dataset
- **File:** `titanicsurvival.csv`  
- Contains passenger details like:
  - `PassengerId`
  - `Pclass`
  - `Name`
  - `Sex`
  - `Age`
  - `SibSp`, `Parch`
  - `Fare`
  - `Embarked`
  - `Survived` (target variable)

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data manipulation  
- [numpy](https://numpy.org/) – Numerical computations  
- [matplotlib](https://matplotlib.org/) – Data visualization  
- [seaborn](https://seaborn.pydata.org/) – Statistical plots  
- [scikit-learn](https://scikit-learn.org/stable/) – Naive Bayes model  

---

## 📊 Project Workflow
1. Import required libraries.  
2. Load and explore the Titanic dataset.  
3. Clean and preprocess the data.  
4. Train the Naive Bayes classifier.  
5. Make predictions on unseen data.  
6. Evaluate performance metrics.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sachin-183/titanic-naive-bayes.git
   cd titanic-naive-bayes
