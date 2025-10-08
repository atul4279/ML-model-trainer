# 📊 Streamlit ML model Trainer

An interactive **Streamlit app** for training and evaluating Machine Learning models on your own CSV datasets. Supports both **classification** and **regression** tasks.

## 🚀 Features

* Upload your CSV file and preview the dataset.
* Automatically handles missing values and encodes categorical variables.
* Choose target column and task type (Classification or Regression).
* Train and evaluate multiple ML models:

  * Classification: Logistic Regression, Random Forest, SVM
  * Regression: Linear Regression, Random Forest Regressor, SVR
* Displays key performance metrics:

  * Classification: Accuracy, Precision, Recall, F1-score, Confusion Matrix, Classification Report
  * Regression: MAE, MSE, RMSE, R² score

## 🛠 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/streamlit-ml-trainer.git
cd streamlit-ml-trainer
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run app_ml_model.py
```



## 📊 Usage

1. Upload a CSV file.
2. Select the target column.
3. Choose task type (Classification or Regression).
4. Pick a model.

