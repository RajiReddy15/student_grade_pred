# 🎓 Student Grade Prediction

This project aims to predict student final grades based on various academic and personal attributes using machine learning models.

## 📌 Project Overview

The objective is to build a predictive model that can estimate students' final grades using features such as past academic performance, study time, absences, and other factors. This can help educators identify students who may need extra support.

## 📂 Dataset

The dataset contains features such as:

- First and second period grades
- Study time, absences
- Parental education
- Past failures
- Other demographic and academic attributes

Target variable: **Final Grade**

## 🛠️ Tech Stack

- **Python**
- **pandas** – Data loading & manipulation  
- **numpy** – Numerical computations  
- **matplotlib & seaborn** – Data visualization  
- **scikit-learn** – Model building and evaluation

## 📊 Exploratory Data Analysis (EDA)

- Handled missing values and removed irrelevant features
- Visualized correlations using heatmaps and pairplots
- Analyzed the impact of key factors (e.g., study time, absences) on final grades

## 🤖 Models Used

- Linear Regression
- Random Forest Regressor

### 📈 Model Evaluation

- Used metrics like MAE, RMSE, and R² Score
- Compared performance between models on test data

## 📌 Results

- Random Forest outperformed other models with higher accuracy on unseen data
- Identified key factors influencing academic performance

## 🚀 How to Run

1. Clone this repository  
2. Install dependencies from `requirements.txt`  
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook main.ipynb
   ```

## 📁 Project Structure

```
student_grade_prediction/
├── main.ipynb
├── requirements.txt
├── README.md
├── datasets/
│   ├── student-mat.csv
│   └── student-por.csv
```

## 📬 Contact

For questions or collaboration, feel free to connect on [LinkedIn](https://www.linkedin.com/in/raji-reddy-bb54682aa/).
