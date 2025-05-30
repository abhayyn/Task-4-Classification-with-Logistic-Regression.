# 🧠 Task 4: Binary Classification using Logistic Regression

- **Dataset Used**: [Breast Cancer Wisconsin Diagnostic Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Classes**: 
  - Malignant (1)
  - Benign (0)

## Workflow

1. **Data Loading & Cleaning**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Encoded target labels (M → 1, B → 0)

2. **Data Preprocessing**
   - Train-test split (80-20)
   - Feature standardization using `StandardScaler`

3. **Modeling**
   - Logistic Regression from `scikit-learn`
   - Used `predict` and `predict_proba` for predictions

4. **Evaluation Metrics**
   - **Confusion Matrix**
   - **Precision**
   - **Recall**
   - **ROC-AUC Score**
   - **ROC Curve Visualization**

5. **Threshold Tuning**
   - Changed decision threshold to 0.4
   - Compared precision and recall under custom threshold

6. **Sigmoid Function**
   - Visualized the sigmoid activation curve to show how outputs are mapped to probabilities.
   - 
## Tools & Libraries
- Python 3
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

## 🖼️ Visuals
- ROC Curve
- Sigmoid Function Curve

