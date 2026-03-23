#  Titanic Survival Prediction using Logistic Regression

##  Project Overview

This project predicts whether a passenger survived the Titanic disaster using **Machine Learning (Logistic Regression)**.
It includes a complete pipeline from **data preprocessing to model training, evaluation, and saving**.

---

##  Problem Statement

Predict the survival of passengers based on features like:

* Age
* Fare
* Sex
* Embarked
* Other passenger details

---

## Technologies Used

* Python 
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

##  Project Structure

```
Titanic_CaseStudy/
│
├── Titanic_CaseStudy.py
├── MarvellousTitanicDataset.csv
├── marvelloustitanic.pkl
└── README.md
```

---

## Steps Performed

### 1️⃣ Data Loading

* Dataset loaded using Pandas

### 2️⃣ Data Preprocessing

* Removed unnecessary columns
* Handled missing values (Age, Fare, Embarked)
* Converted categorical data to numeric
* Encoding using `get_dummies()`

### 3️⃣ Model Training

* Algorithm: **Logistic Regression**
* Data split into training and testing sets (80/20)

### 4️⃣ Model Evaluation

* Accuracy Score
* Confusion Matrix

### 5️⃣ Model Saving

* Model saved using **Joblib (.pkl file)**
* Reloaded for prediction

---

##  Model Performance

* Accuracy: ~ (Add your output here, e.g., 0.94)

---

## ▶ How to Run

### Step 1: Install dependencies

```
pip install pandas numpy scikit-learn joblib
```

### Step 2: Run the program

```
python Titanic_CaseStudy.py
```

---

##  Output

* Displays dataset information
* Shows preprocessing steps
* Prints model accuracy
* Displays confusion matrix

---

##  Key Learnings

* Data preprocessing techniques
* Handling missing values
* Feature encoding
* Model training & evaluation
* Model persistence using Joblib

---

##  Author

**Sakshi Vishwas Kalamkar**

---

## Future Improvements

* Add visualization (matplotlib / seaborn)
* Try advanced models (Random Forest, SVM)
* Hyperparameter tuning
* Build a web app using Flask/Streamlit

---

##  Conclusion

This project demonstrates a complete **end-to-end Machine Learning pipeline** and is suitable for:

* Beginners learning ML
* Academic projects
* Resume & GitHub portfolio

---
