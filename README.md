# Lung Cancer Survival Prediction #

# Overview
This project predicts the survival chances of lung cancer patients based on their medical history and lifestyle factors. It implements **Machine Learning (XGBoost)** and **Deep Learning (Neural Networks)** to compare model performance and identify key predictors.

This project was completed as part of my **internship**, where I focused on data preprocessing, feature engineering, model development, and evaluation to derive meaningful insights.

# Dataset
The dataset contains patient records, including medical conditions, demographics, and lifestyle factors. Key features include:
- **Age, Gender, Country**
- **Cancer Stage, Family History**
- **Smoking Status, BMI, Hypertension, Asthma**
- **Treatment Type, Cholesterol Level**
- **Survival Status (Target Variable)**

# My Role & Contributions
- **Data Preprocessing**: Cleaning, handling missing values, encoding categorical features, and balancing the dataset using SMOTE.
- **Exploratory Data Analysis (EDA)**: Identified key predictors using statistical visualizations.
- **Model Development**: Built and optimized XGBoost and Neural Networks for prediction.
- **Feature Importance Analysis**: Used SHAP to interpret the model’s decisions.
- **Deployment**: Developed a Flask API for real-time predictions (optional for deployment).

# Project Workflow
1. **Data Preprocessing**  
   - Handle missing values
   - Encode categorical features
   - Scale numerical features
   - Balance dataset using SMOTE

2. **Exploratory Data Analysis (EDA)**  
   - Visualize feature distributions
   - Check correlations
   - Identify key predictors

3. **Model Training & Evaluation**  
   - Train **XGBoost (Machine Learning)**
   - Train **Deep Neural Network (Deep Learning)**
   - Compare models based on Accuracy, Precision, Recall, F1-score

4. **Feature Importance Analysis**  
   - Use SHAP to explain predictions
   - Identify most influential features

5. **Deployment**  
   - Build **Flask API** for real-time predictions
   - Host on cloud platform (optional)

# Technologies Used
- **Python (Pandas, NumPy, Scikit-Learn, TensorFlow, XGBoost, SHAP)**
- **Jupyter Notebook for development**
- **Flask for deployment**

# Results & Insights
- **XGBoost performed well** with good explainability.
- **Neural Networks showed improved accuracy** but required more training data.
- **Smoking Status, Cancer Stage, and BMI were key predictors.**

# How to Run the Project
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/lung-cancer-prediction.git
   cd lung-cancer-prediction
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook for model training**
4. **Start Flask API for predictions**
   ```sh
   python app.py
   ```

# Future Improvements
- Optimize hyperparameters for better performance
- Deploy on cloud (AWS, GCP, or Heroku)
- Use larger and more diverse datasets

# Contributors
- **Revati Mahajan** - Data Science & Machine Learning Engineer (Intern)

# License
This project is licensed under the MIT License.

