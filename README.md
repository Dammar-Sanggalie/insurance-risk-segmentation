# Insurance Risk Segmentation & Classification

## Project Overview
This project focuses on customer risk segmentation and classification
for health insurance data using demographic and lifestyle attributes.

The objective is to identify meaningful risk patterns and build
interpretable machine learning models that support:
- Risk-based pricing strategies
- Customer segmentation
- Data-driven decision making in insurance businesses

The project follows a complete data science lifecycle,
from exploratory analysis to model interpretability.

---

## Dataset
Public health insurance dataset containing:
- Age
- Sex
- BMI
- Smoking status
- Region
- Medical charges

A risk label is engineered based on medical charges
and categorized into three classes:
**Low**, **Medium**, and **High risk**.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Risk segmentation based on medical charges
- BMI categorization (Normal, Overweight, Obese)
- Composite risk profiling (Smoking status + BMI)
- Business-oriented visual insights

### 2. Feature Engineering
- Encoding categorical variables
- Feature scaling
- Target variable preparation for classification
- ML-ready dataset creation

### 3. Modeling
- Multiclass classification using Logistic Regression
- Train-test split with stratification
- Probabilistic prediction outputs

### 4. Model Evaluation
- Confusion Matrix (3-class classification)
- ROC Curve & AUC (One-vs-Rest strategy)
- Classification report (Precision, Recall, F1-score)

### 5. Model Interpretability
- SHAP (SHapley Additive exPlanations)
- Global feature importance visualization
- Transparent and explainable risk predictions

---

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn
- SHAP
- Jupyter Notebook

---

## Project Structure
# Insurance Risk Segmentation & Classification

## Project Overview
This project focuses on customer risk segmentation and classification
for health insurance data using demographic and lifestyle attributes.

The objective is to identify meaningful risk patterns and build
interpretable machine learning models that support:
- Risk-based pricing strategies
- Customer segmentation
- Data-driven decision making in insurance businesses

The project follows a complete data science lifecycle,
from exploratory analysis to model interpretability.

---

## Dataset
Public health insurance dataset containing:
- Age
- Sex
- BMI
- Smoking status
- Region
- Medical charges

A risk label is engineered based on medical charges
and categorized into three classes:
**Low**, **Medium**, and **High risk**.

---

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Risk segmentation based on medical charges
- BMI categorization (Normal, Overweight, Obese)
- Composite risk profiling (Smoking status + BMI)
- Business-oriented visual insights

### 2. Feature Engineering
- Encoding categorical variables
- Feature scaling
- Target variable preparation for classification
- ML-ready dataset creation

### 3. Modeling
- Multiclass classification using Logistic Regression
- Train-test split with stratification
- Probabilistic prediction outputs

### 4. Model Evaluation
- Confusion Matrix (3-class classification)
- ROC Curve & AUC (One-vs-Rest strategy)
- Classification report (Precision, Recall, F1-score)

### 5. Model Interpretability
- SHAP (SHapley Additive exPlanations)
- Global feature importance visualization
- Transparent and explainable risk predictions

---

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn
- SHAP
- Jupyter Notebook

---

## Project Structure
insurance-risk-segmentation/
├── data/ # Raw and processed datasets
├── notebooks/ # EDA, feature engineering, modeling
├── src/ # Utility scripts (if any)
├── README.md


---

## Key Insights
- Smoking status and BMI are dominant drivers of insurance risk
- High-risk customers are more confidently classified by the model
- Most misclassifications occur between adjacent risk levels
- SHAP analysis enhances trust and transparency in predictions

---

## Future Improvements
- Experiment with tree-based models (Random Forest, XGBoost)
- Hyperparameter tuning
- Cost-sensitive learning
- Deployment as an interactive dashboard or API

---

## Author
**Dammar Sanggalie**  
Machine Learning & Data Science Enthusiast