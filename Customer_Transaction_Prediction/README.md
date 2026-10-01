# Customer Transaction Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a customer will complete a transaction using Machine Learning classification techniques.

The project follows an end-to-end Machine Learning workflow, including data cleaning, data preprocessing, outlier analysis, handling class imbalance, feature scaling, model training, model evaluation, and model comparison.

The main objective is to identify patterns in customer transaction data and build classification models capable of predicting the target transaction outcome.

---

## 🎯 Objectives

- Analyze customer transaction data.
- Perform data cleaning and preprocessing.
- Identify and analyze outliers.
- Handle class imbalance appropriately.
- Prepare data for Machine Learning models.
- Train multiple classification algorithms.
- Evaluate models using appropriate performance metrics.
- Compare different Machine Learning models.
- Identify a suitable candidate model based on performance and interpretability.

---

## 🛠️ Technologies & Libraries

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Imbalanced-learn**
- **Jupyter Notebook**

---

## 🔄 Machine Learning Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Quality Checks
      ↓
Exploratory Data Analysis
      ↓
Outlier Analysis
      ↓
Train-Test Split
      ↓
Class Imbalance Handling
      ↓
Feature Scaling
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
Final Prediction
```

---

## 🤖 Machine Learning Models

The following classification algorithms are implemented and compared:

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier
4. Linear SVM
5. Decision Tree Classifier
6. Gradient Boosting Classifier

---

## ⚙️ Data Preprocessing

The following preprocessing steps are performed:

- Dataset inspection
- Missing-value analysis
- Duplicate-value checking
- Data type verification
- Removal of unnecessary identifier columns
- Train-test splitting
- Feature scaling
- Class imbalance handling

The dataset is split using stratification to maintain the target-class distribution between training and testing datasets.

---

## ⚖️ Class Imbalance Handling

The target variable contains imbalanced classes.

Random Under-Sampling is applied to the **training data only** to reduce class imbalance.

The test dataset is kept unchanged so that final model performance can be evaluated on the original class distribution.

This helps avoid information leakage from the test set.

---

## 🔎 Outlier Analysis

Outliers are identified using the **Interquartile Range (IQR)** method.

Instead of automatically removing all detected outliers, the project analyzes their presence because extreme transaction-related observations may contain useful information for predicting customer behavior.

Therefore, outlier detection and outlier removal are treated as separate processes.

---

## 📊 Model Evaluation

The models are evaluated using multiple classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

Because the target classes are imbalanced, **Precision, Recall, F1-Score, and ROC-AUC** are considered important metrics in addition to accuracy.

### Why these metrics?

**Precision:** Measures how many predicted positive transactions are actually positive.

**Recall:** Measures how many actual positive transactions are correctly identified.

**F1-Score:** Provides a balance between Precision and Recall.

**ROC-AUC:** Measures the model's ability to distinguish between the two target classes across different classification thresholds.

---

## 📈 Model Comparison

The trained models are compared using the evaluation metrics mentioned above.

The comparison helps understand the strengths and weaknesses of different classification algorithms rather than relying on a single metric.

Logistic Regression provides competitive predictive performance while also offering good interpretability, making it a suitable candidate model for understanding the relationship between input features and the target outcome.

---

## 🔬 Key Machine Learning Concepts Demonstrated

This project demonstrates practical knowledge of:

- Supervised Learning
- Binary Classification
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Stratified Sampling
- Class Imbalance
- Random Under-Sampling
- Outlier Detection
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- XGBoost
- Support Vector Machine
- Model Evaluation
- ROC-AUC
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📂 Project Structure

```text
Customer-Transaction-Prediction/
│
├── Customer Transaction Prediction.ipynb
├── README.md
├── requirements.txt
│
└── dataset/
    └── customer_transaction.csv
```

---

## 🚀 Future Improvements

The following improvements can be explored in future versions:

- Stratified K-Fold Cross-Validation
- Comparison of different class-imbalance techniques
- Hyperparameter tuning
- Feature importance analysis
- Classification threshold analysis
- Model interpretability
- Model deployment using Flask or FastAPI
- Development of a web interface for real-time predictions

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Customer-Transaction-Prediction.git
```

Navigate to the project directory:

```bash
cd Customer-Transaction-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Customer Transaction Prediction.ipynb
```

---

## 📌 Conclusion

This project demonstrates an end-to-end Machine Learning approach for customer transaction prediction.

It covers the complete workflow from data cleaning and preprocessing to handling class imbalance, analyzing outliers, training multiple classification models, evaluating their performance, and comparing the results.

The project provides practical experience in building and evaluating Machine Learning classification models on real-world-style customer transaction data.

---

## 👨‍💻 Skills Demonstrated

**Python | NumPy | Pandas | Data Cleaning | Data Preprocessing | Exploratory Data Analysis | Outlier Analysis | Feature Scaling | Class Imbalance | Machine Learning | Classification | Scikit-learn | XGBoost | Model Evaluation**

---

## 📜 License

This project is intended for educational and portfolio purposes.