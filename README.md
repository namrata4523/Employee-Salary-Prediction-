# 👩‍💻 Employee Salary Prediction Web App

Welcome to the **Employee Salary Prediction** project!  
This application uses machine learning to predict employee salaries based on various features such as experience, education, skill level, company revenue, and more.

---

## 📁 Project Files

- `employee_salary_prediction_namrata233.ipynb` — Main Jupyter notebook with preprocessing, model training, and evaluation
- `employee_data.csv` — Dataset used for training and testing
- `streamlit_interface.png` — Screenshot of the deployed Streamlit app
- `README.md` — Project overview and instructions

---

## 📊 Machine Learning Overview

This project applies machine learning algorithms to predict employee salaries.  
Various regression models like:

- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Decision Tree Regressor  

were tested and compared to select the best-performing model.

✅ The final model was selected based on the highest **accuracy score**.

---

## 🚀 Web App Interface

The following Streamlit app interface allows users to:
- Upload their CSV dataset
- View sample data
- Predict salaries based on the uploaded features

📸 **Streamlit Screenshot:**

![Streamlit Interface](https://raw.githubusercontent.com/namrata4523/Employee-Salary-Prediction-/d5e589a9b4134c33db04aa299f25769b0071c66f/1streamlit_interface.png.png)

---

## 📈 Model Accuracy Screenshot

📸 Screenshot of ML model evaluation showing accuracy of different algorithms and the selected best model:

![Model Accuracy](https://raw.githubusercontent.com/namrata4523/Employee-Salary-Prediction-/main/2model_accuracy.png)

---

## 🧠 Features Used

The model considers features like:
- Years of Experience
- Education Level
- Skill Rating
- City Cost of Living Index
- Company Revenue
- Previous Promotions
- Project Impact Score

These were selected to improve prediction accuracy and make the system industry-ready.

---

## 🔧 Technologies Used

- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Streamlit (for UI)  
- Jupyter Notebook  

---

## 📥 How to Run

### ▶️ Run Locally via Jupyter Notebook
1. Clone the repository
2. Open the `.ipynb` file
3. Run cells step by step

### 🌐 Launch Streamlit App
```bash
streamlit run app.py
