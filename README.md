# 🍷 Wine Quality Prediction

Predict wine quality (Low/Medium/High) using machine learning models based on chemical properties.

## 📊 Project Overview
- Dataset: [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- Features: acidity, sugar, chlorides, pH, alcohol, etc.  
- Target: wine quality score (1–10), binned into **Low (≤5), Medium (6–7), High (≥8)** for better classification.  

## 🤖 Models Implemented
- Logistic Regression (baseline)
- Random Forest Classifier
- XGBoost Classifier (best performance)

## 🔍 Exploratory Data Analysis (EDA)
- Distribution of wine quality scores
- Feature importance analysis
- Confusion matrix for model evaluation  

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ritesh30001/wine-quality-ml.git

2. Install dependencies:
  pip install -r requirements.txt
3. Open wine_quality_notebook.ipynb in Jupyter Notebook or JupyterLab.
4. Run each cell sequentially.

Results:
Models trained to predict binned wine quality.
Accuracy: ~70–75% with XGBoost.
Confusion matrices and feature importance visualizations included.
 
Dataset :Red Wine CSV from UCI Wine Quality Dataset:https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv?utm_source=chatgpt.com

Notes:
Fully compatible with Mac M1.
Features normalized using StandardScaler.
Binning improves classification performance due to imbalanced labels.

Author
Ritesh : https://github.com/ritesh30001




