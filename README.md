# Heart Failure Prediction using Machine Learning

## 📌 Overview
This project uses the [Heart Failure Clinical Records Dataset](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data) to build predictive models for **heart failure mortality**.  
The goal is to classify whether a patient will experience a **death event** based on their clinical data.

## 📊 Dataset
- **Source:** Kaggle – Heart Failure Clinical Records  
- **Samples:** 299 patients  
- **Features:** 12 clinical attributes (e.g., age, anaemia, creatinine, ejection fraction, serum sodium)  
- **Target:** `DEATH_EVENT` (1 = patient died, 0 = patient survived)

## ⚙️ Methods
The workflow includes:
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature scaling using `StandardScaler`  
4. Model training with cross-validation  
5. Model comparison (Logistic Regression, Random Forest, Gradient Boosting, etc.)  
6. Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC AUC  

## 🛠️ Technologies
- Python  
- Pandas, NumPy  
- scikit-learn  
- Matplotlib, Seaborn  

## 🚀 Usage
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/heart-failure-prediction.git
cd heart-failure-prediction
pip install -r requirements.txt
