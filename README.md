# Telecom Customer Churn Prediction (ML)

A machine learning project that predicts whether a telecom customer is likely to leave (churn), so the business can act early with targeted retention offers.

---

## Problem Statement

Customer churn directly hurts revenue in the highly competitive telecom industry, and acquiring a new customer usually costs far more than keeping an existing one. This project builds a classification model that flags customers at high risk of churning based on their demographics, account details and the services they use.

## Dataset

<!-- TODO: Confirm this matches the dataset you used -->
- **Source:** [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** ~7,043 customers, 21 columns
- **Target:** `Churn` (Yes / No)
- **Feature groups:**
  - *Demographics:* gender, senior citizen, partner, dependents
  - *Services:* phone, multiple lines, internet, online security, backup, tech support, streaming
  - *Account:* tenure, contract type, paperless billing, payment method, monthly and total charges

## Methodology

1. **Data cleaning:** handle missing/blank values (e.g. `TotalCharges`), fix data types, remove duplicates
2. **Exploratory data analysis (EDA):** churn distribution and relationships between features and churn
3. **Preprocessing:** encode categorical variables, scale numeric features, handle class imbalance
4. **Model training:** train and compare multiple classifiers
5. **Evaluation:** accuracy, precision, recall, F1-score, ROC-AUC and confusion matrix
6. **Hyperparameter tuning** of the best-performing model <!-- TODO: remove if not done -->

### Models Used
<!-- TODO: Edit this list to match your notebook -->
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Support Vector Machine
- Gradient Boosting / XGBoost

## Results

<!-- TODO: Replace with your actual numbers -->
| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | - | - | - | - | - |
| Random Forest | - | - | - | - | - |
| [Best Model] | - | - | - | - | - |

**Key insights** <!-- TODO: Update with your findings -->
- Customers on month-to-month contracts churn more than those on longer contracts
- Short-tenure customers are at the highest risk
- [Add more findings from your EDA]

## Tech Stack

- **Language:** Python 3.x
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Environment:** Jupyter Notebook

## Project Structure

<!-- TODO: Update to match your actual repo -->
```
Telecom-Customer-ChurnPrediction-ML_/
├── data/                 # Dataset (CSV)
├── notebooks/            # EDA and model training notebooks
├── models/               # Saved trained model(s)
├── requirements.txt      # Python dependencies
└── README.md
```

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/nikhilwagh77/Telecom-Customer-ChurnPrediction-ML_.git
cd Telecom-Customer-ChurnPrediction-ML_
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the notebook
```bash
jupyter notebook
```
Then open the notebook and run all cells.

## Future Improvements

- Deploy the model as a web app (Streamlit / Flask / FastAPI)
- Add model explainability with SHAP
- Try advanced models and further hyperparameter tuning
- Build a retention-strategy dashboard

## Contributing

Contributions, issues and feature requests are welcome. Feel free to open an issue or submit a pull request.

## Author

**Nikhil Wagh**
GitHub: [@nikhilwagh77](https://github.com/nikhilwagh77)

## License

<!-- TODO: Add a license (e.g. MIT) or remove this section -->
This project is licensed under the MIT License.
