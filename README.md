# Lung Cancer Survival Prediction #

# Project Overview
This project aims to predict the survival of lung cancer patients based on medical and demographic data. It utilizes both **Machine Learning (XGBoost)** and **Deep Learning (Neural Networks)** to analyze and compare model performance. The dataset consists of patient records, including attributes such as age, cancer stage, smoking status, BMI, and treatment type.

# Dataset Information
The dataset includes **890,000 patient records** with the following key features:
- `id`: Unique patient identifier
- `age`: Age at diagnosis
- `gender`: Male/Female
- `cancer_stage`: Stage I-IV
- `smoking_status`: Current smoker, former smoker, never smoked, passive smoker
- `bmi`: Body Mass Index
- `hypertension`, `asthma`, `cirrhosis`, `other_cancer`: Comorbidities
- `treatment_type`: Surgery, chemotherapy, radiation, combined
- `survived`: Target variable (Yes/No)

📂 Dataset Access
-  Due to GitHub's file size limitations, the dataset is hosted externally. You can download it from:
   Google Drive Link - https://drive.google.com/file/d/1beHH6goLrHpMk5z1hp8Ar5UFtJ6Lv8Fz/view?usp=drive_link


# Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling (Standardization)
   - Balancing classes using **SMOTE**

2. **Model Training**
   - **XGBoost (Machine Learning)**: Feature importance analysis with SHAP
   - **Deep Learning (Neural Network)**: Multi-layer perceptron (MLP) architecture

3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix & ROC Curve
   - Comparison of ML vs. Deep Learning

4. **Deployment (Optional)**
   - Flask API for real-time predictions
   - Deployment on **AWS/Heroku**

# Results & Findings
- **XGBoost achieved 78% accuracy**, providing interpretable predictions via SHAP.
- **Neural Networks reached 50% accuracy**, not showing better performance but requiring more computation.
- **Feature importance**: Cancer stage, smoking status, and BMI were the top predictors.
- **Survival rate trends**: Patients diagnosed at an early stage had significantly higher survival chances.

# How to Run the Project
### 1️⃣ Install Dependencies
```bash
pip install pandas numpy scikit-learn xgboost tensorflow flask
```

### 2️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```
Open and execute `Lung_Cancer_Prediction.ipynb`

### 3️⃣ Deploy Flask API (Optional)
```bash
python app.py
```

# Future Scope
- **Improve Deep Learning architecture** using CNN/LSTM for better feature extraction.
- **Deploy as a web app** with real-time data entry and prediction.
- **Integrate Explainable AI (XAI)** for model transparency.

# Key Skills Gained
✅ **Machine Learning & Deep Learning**
✅ **Feature Engineering & Data Preprocessing**
✅ **Model Comparison & Evaluation**
✅ **Flask API for Deployment**

---

# Connect with Me
**GitHub**: [github.com/Revati07](https://github.com/Revati07)  
**LinkedIn**: [linkedin.com/in/revatimahajan](https://linkedin.com/in/revatimahajan)





