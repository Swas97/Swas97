# 🛡️ Fraud Detection using Machine Learning

This project presents an end-to-end pipeline to detect fraudulent transactions using classification models on a highly imbalanced dataset. It combines **Python-based ML modeling** and **Power BI visualizations** for business interpretability.

---

## 📌 Project Objectives

- Detect fraudulent transactions in real-time using machine learning.
- Handle **class imbalance** using SMOTE and model weighting techniques.
- Deliver **data-driven insights** and **interactive dashboards** for business stakeholders.

---

## 🔧 Tools & Technologies

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Imbalanced-learn, Matplotlib, Seaborn
- **Modeling**: Decision Tree, Random Forest, XGBoost
- **Dashboard**: Power BI (`.pbix`)
- **Environment**: Jupyter Notebook

---

## 🧪 ML Pipeline Workflow

1. **Data Preprocessing**
   - Outlier removal and missing value handling
   - Feature scaling with `StandardScaler`
   - Label encoding for categorical variables
   - Class imbalance handled using **SMOTE**

2. **Exploratory Data Analysis**
   - Transaction pattern visualization
   - Feature correlation and distribution analysis
   - Fraud vs Non-Fraud trend analysis

3. **Model Training**
   - Applied **Decision Tree**, **Random Forest**, and **XGBoost**
   - Hyperparameter tuning with `GridSearchCV`
   - `class_weight='balanced'` to adjust for class skew

4. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Confusion Matrix & Classification Report
   - Focused on minimizing **false negatives** to reduce fraud risk

5. **Dashboard (Power BI)**
   - Fraud rate trends
   - Model performance comparison
   - Visual insights for business decision-making

---

## 📈 Results Summary

| Metric              | Value   |
|---------------------|---------|
| **Accuracy**        | 92%     |
| **ROC AUC Score**   | 0.4908  |
| **Macro F1-Score**  | 0.49    |
| **Weighted F1-Score** | 0.91  |

> ⚠️ Note: The baseline model showed bias toward the majority class. SMOTE and tuning improved fraud detection capabilities.

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard (`Fraud_Detection.pbix`) is included to present:
- Fraud distribution by feature
- Monthly trends in fraud activity
- Model evaluation and classification breakdown

---

## 📁 Project Structure

