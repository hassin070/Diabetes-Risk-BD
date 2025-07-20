
# 🩺 Diabetes-Risk-BD

This project leverages the **DiaBD** dataset to analyze and predict diabetes risk among patients in **Bangladesh** using machine learning. It includes preprocessing, feature engineering, model training, evaluation, and visualizations.

---

## 📊 Dataset

**DiaBD** is a publicly available dataset containing **5,288 patient records** from Bangladesh. It includes:
- Demographics (age, gender)
- Clinical features (blood pressure, glucose, BMI)
- Family history (diabetes, hypertension, cardiovascular disease)
- Binary diabetes status (Yes/No)

📁 [Dataset Source (Mendeley Data)](https://data.mendeley.com/datasets/m8cgwxs9s6/2)

---

## 🧠 Project Goals

- Explore patterns and correlations in Bangladeshi diabetes cases
- Build ML models to predict diabetes risk
- Evaluate and compare model performance
- Provide visual insight into risk factors

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Jupyter Notebooks  

---

## 🔄 Workflow

1. **Data Cleaning**
   - Handle missing values
   - Encode categorical columns (`gender`, `yes/no` fields)

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots, correlation matrix, class balance

3. **Feature Engineering**
   - Transform categorical variables
   - Normalize/scale if necessary

4. **Modeling**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine
   - (Optional: XGBoost, Neural Net)

5. **Evaluation**
   - Accuracy, Precision, Recall, F1 Score, ROC-AUC
   - Confusion Matrix

6. **Interpretation**
   - Feature importance
   - Risk factor insights

---

## 📈 Results

_Results will be updated as the project progresses._  
Initial models show promising accuracy in identifying key diabetes risk indicators in the Bangladeshi population.

---

## 📂 Folder Structure

```
Diabetes-Risk-BD/
├── data/               # Dataset or link to external source
├── notebooks/          # Jupyter notebooks for EDA, modeling
├── src/                # Python scripts
├── results/            # Charts, evaluation reports
├── README.md           # Project overview
└── requirements.txt    # Python dependencies
```

---

## ✅ To-Do

- [ ] Add Streamlit app for risk prediction  
- [ ] Compare advanced models (XGBoost, Ensemble)  
- [ ] Improve model explainability (SHAP, LIME)  

---

## 📌 License

This project is open-sourced under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [DiaBD Dataset (Mendeley)](https://data.mendeley.com/datasets/m8cgwxs9s6/2)  
- Developed by [Hassin Arman](https://github.com/hassin070)

---

## 💬 Feedback or Collaboration?

Feel free to open an issue or reach out via GitHub.

