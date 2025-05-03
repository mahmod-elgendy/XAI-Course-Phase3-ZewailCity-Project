
# XAI-Course-Phase3-ZewailCity-Project

This repository contains our final project for the **Explainable AI (XAI) Course - Phase 3** at Zewail City. The project aims to explore the performance and interpretability of various machine learning models applied to the heart disease prediction dataset.

---

## 📁 File Structure

- `heart_statlog_cleveland_hungary_final.csv`: The cleaned dataset combining Cleveland and Hungary heart disease data.
- `XAI_Phase_3_EDA.ipynb`: Exploratory Data Analysis (EDA) to understand data distribution, correlations, and preprocessing steps.
- Individual notebooks implementing 9 different machine learning models:
  - `KNN_model.ipynb`
  - `MLP_mode.ipynb`
  - `Naive_Bayes_Model.ipynb`
  - `RandomForest_XAI_Phase_3.ipynb`
  - `LGBM_XAI_Phase_3.ipynb`
  - `XGBoost_XAI_Phase_3.ipynb`
  - `XAI_phase3_DecisionTreeAsmaa_(2).ipynb`
  - `XAI_phase3_LogisticRegressionAsmaa_(2).ipynb`
  - `XAI_phase3_SVM_Asmaa_(2).ipynb`

---

## 🤖 Machine Learning Models Implemented

The project includes the implementation and evaluation of the following classification models:
- K-Nearest Neighbors (KNN)
- Multi-Layer Perceptron (MLP)
- Naive Bayes
- Random Forest
- LightGBM (LGBM)
- XGBoost
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree

Each model was trained, tested, and evaluated with performance metrics such as accuracy, precision, recall, and F1-score.

---

## 🔍 Explainability Techniques

Four Explainable AI (XAI) methods were applied across different models from each Student:
These techniques help to interpret the predictions and understand which features are most influential for each model.
Even one of them is user friendly explaination.

---

## 👥 Team Contributions

| Name              | Contributions                                                                 |
|-------------------|--------------------------------------------------------------------------------|
| **Mahmoud Elgendy**  | Implemented: XGBoost, LGBM, Random Forest models                            |
| **Toqa Hassan**      | Implemented: KNN, MLP, Naive Bayes models                                   |
| **Asmaa Eldesoky**   | Implemented: SVM, Logistic Regression, Decision Tree models                 |

---

## 🏫 Course Info

**Course**: Explainable AI (XAI)  
**Phase**: 3  
**Institution**: Zewail City of Science and Technology  
**Project**: Final course project exploring XAI with classical and ensemble ML models

---

## ▶️ How to Run This Project on Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` notebook file you want to run.
3. Upload the dataset file `heart_statlog_cleveland_hungary_final.csv` using:
   ```python
   from google.colab import files
   files.upload()
   ```
4. Make sure to install any required packages (e.g., shap, lime, lightgbm):
   ```python
   !pip install shap lime lightgbm
   ```
5. Run all cells in the notebook to execute the model training and explanation.

---

## 📝 License

This project is intended for educational use only.
