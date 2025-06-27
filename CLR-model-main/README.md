Logistic Regression Classifier - Breast Cancer Prediction

 Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  



Workflow

1. Data Preprocessing
- Removed `id` and `Unnamed: 32` columns.
- Converted `diagnosis` column to numeric binary values.
- Standardized the features using `StandardScaler`.

2. Model Building
- Used **Logistic Regression** from Scikit-learn.
- Split data into training and test sets (80/20 split).

3. Evaluation Metrics
- Confusion Matrix 
- Precision, Recall, F1-Score (from `classification_report`)  
- ROC-AUC Score & ROC Curve
