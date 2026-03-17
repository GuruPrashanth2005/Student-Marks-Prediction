# 📊 Student Marks Prediction

## 📌 Project Overview
This project predicts student exam scores using machine learning regression models.  
The prediction is based on factors like study hours, sleep, attendance, and previous scores.

---

## 🎯 Problem Statement
- Predict the **exam_score** of students  
- This is a **regression problem** because the output is a continuous value  
- Target variable: **exam_score**

---

## 📂 Dataset
Columns used:
- student_id
- hours_studied
- sleep_hours
- attendance_percent
- previous_scores
- exam_score (target)

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## ⚙️ Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  
- Checked structure and columns  

### 2. Data Understanding
- Checked datatypes  
- Checked missing values  
- Used describe() for summary  

### 3. Data Preprocessing
- Handled missing values using mean  
- Applied encoding (if needed)  

### 4. Train-Test Split
- Split data into training and testing sets  
- test_size = 0.2  
- random_state = 42  

### 5. Model Building
Models used:
- Linear Regression (mandatory)
- Ridge Regression
- Lasso Regression
- Polynomial Regression

### 6. Prediction
- Predicted exam scores using test data  

### 7. Model Comparison
- Compared models using predictions  
- Visualized actual vs predicted values  

### 8. Visualization
- Scatter plot (Actual vs Predicted)  
- Regression line  
- Residual plot  

---

## 📈 Results
- Models successfully predicted student marks  
- Best model: *(mention based on your result)*  
- Good performance when predictions are close to actual values  

---

## 🧠 Conclusion
- Learned how regression models work  
- Understood importance of preprocessing and evaluation  
- Ridge/Lasso help reduce overfitting  
- Linear Regression works well for simple relationships  

---

## ⚠️ Challenges Faced
- Handling missing data  
- Understanding model differences  
- Fixing coding errors (NameError, etc.)  

---

## 🚀 Future Improvements
- Use larger dataset  
- Try advanced models (Random Forest, XGBoost)  
- Improve accuracy with feature engineering  

---

## 👨‍💻 Author
**GURU PRASHANTH S**
