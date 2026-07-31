# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts residential house prices using the Kaggle House Prices dataset. Several machine learning regression models were trained and evaluated to identify the best-performing model. After comparing the results, CatBoost Regressor achieved the highest performance and was selected as the final model.

---

## 📂 Dataset

- **Dataset:** House Prices - Advanced Regression Techniques
- **Source:** Kaggle
- **Training Samples:** 1460
- **Testing Samples:** 1459
- **Target Variable:** SalePrice

---

## 🛠 Technologies Used

- Python 3.11
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- XGBoost
- LightGBM
- CatBoost

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Missing value handling
- Median imputation for numerical features
- "None" replacement for categorical missing values
- Outlier removal
- Log transformation of SalePrice
- Label Encoding
- Feature Engineering (TotalSF)
- Box-Cox transformation for skewed features

---

## 🤖 Machine Learning Models

The following regression models were trained and compared:

- Ridge Regression
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor
- CatBoost Regressor

CatBoost Regressor achieved the best validation performance and was selected as the final model.

---

## 📊 Model Performance

| Metric | Value |
|--------|-------|
| Cross Validation | 5-Fold K-Fold |
| CV RMSE (Mean) | **0.11413** |
| CV RMSE (Std) | **0.00741** |
| Validation RMSE | **0.11597** |
| MAE | **0.07910** |
| R² Score | **0.92022** |

---

## 📁 Project Structure

```
HousePricePrediction/
│── HousePricePrediction.ipynb
│── README.md
│── requirements.txt
│── submission.csv
│── Feature_imp.png
│── residual.png
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/BRINDASRI18/HousePricePrediction.git
cd HousePricePrediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

1. Open Jupyter Notebook:

```bash
jupyter notebook
```

2. Open:

```
HousePricePrediction.ipynb
```

3. Run all notebook cells in order.

---

## 📈 Output

The notebook generates:

- Data preprocessing
- Feature engineering
- Model comparison
- Cross-validation results
- Feature importance visualization
- House price predictions
- `submission.csv`

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Model stacking and ensembling
- SHAP feature interpretation
- Residual error analysis
- Deployment as a web application

---

## 👩‍💻 Author

**Brindasri M**

B.Tech – Artificial Intelligence and Data Science

Ramco Institute of Technology

---

## 🙏 Acknowledgement

This project was developed for academic purposes using the Kaggle House Prices dataset. ChatGPT was used to assist with debugging, code explanations, documentation, and report preparation.
