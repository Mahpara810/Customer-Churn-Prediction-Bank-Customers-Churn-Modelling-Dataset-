# Customer Churn Prediction (Bank Customers)

## 📋 Project Overview
This project focuses on predicting customer churn for a banking institution using machine learning techniques. The goal is to identify customers who are likely to leave the bank, enabling proactive retention strategies.

## 🎯 Objective
- Clean and prepare the churn modeling dataset
- Encode categorical features (Geography and Gender)
- Train classification models to predict customer churn
- Analyze feature importance to understand key factors influencing churn

## 📊 Dataset
**Churn Modelling Dataset** from Kaggle
- **Source**: [Kaggle - Churn Modelling](https://www.kaggle.com/datasets/aakash50897/churn-modellingcsv)
- **Size**: 10,000 records with 14 features
- **Target Variable**: `Exited` (1 = Churned, 0 = Stayed)

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Manipulation: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Machine Learning: scikit-learn
  - Data Download: kaggle API

## 📈 Key Features

### Data Preprocessing
- Removed irrelevant columns (`RowNumber`, `CustomerId`, `Surname`)
- Checked for missing values and duplicates
- Encoded categorical variables (Geography, Gender)
- Analyzed target variable distribution (20.37% churn rate)

### Exploratory Data Analysis
- Target variable distribution visualization
- Categorical feature analysis
- Statistical summary of numerical features

### Machine Learning Models
The project implements and compares multiple classification algorithms:
- Random Forest Classifier
- Gradient Boosting Classifier
- Logistic Regression
- Support Vector Machine (SVC)
- K-Neighbors Classifier

### Model Evaluation
Comprehensive evaluation using:
- Accuracy Score
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score
- Cross-validation

## 🚀 Installation & Setup

### 1. **Clone the repository**
```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction
```
### 2. **Install required dependencies**
```
pip install -r requirements.txt
```
### 3. **Set up Kaggle API (for dataset download)**
- Place your ```kaggle.json ``` file in the appropriate directory

- Update the path in the notebook if needed
  ## 📁 Project Structure  
```md

customer-churn-prediction/
│
├── Customer_Churn_Prediction(Bank Customers).ipynb
├── churn-modelling/
│   └── Churn_Modelling.csv
├── churn-modellingcsv.zip
├── requirements.txt
└── README.md
```
## 🏃‍♂️ Usage
### 1. **Run the Jupyter Notebook:**

```bash
jupyter notebook "Customer_Churn_Prediction(Bank Customers).ipynb"

```

### 2. **Execute cells sequentially to:**
- Download and extract the dataset

- Perform data cleaning and preprocessing

- Conduct exploratory data analysis

- Train and evaluate machine learning models

- Analyze feature importance

## 📊 Results
- Dataset successfully cleaned and prepared

- Multiple classification models trained and evaluated

- Feature importance analysis completed

- Model performance metrics calculated for comparison

## 🎓 Skills Demonstrated
- **Data Preprocessing:** Handling missing values, encoding categorical data

- **Exploratory Data Analysis:** Statistical analysis and visualization

- **Machine Learning:** Supervised classification modeling

- **Model Evaluation:** Comprehensive performance assessment

- **Feature Engineering:** Understanding and interpreting feature importance

## 🤝 Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for suggestions.

## 📄 License
This project is open source and available under the MIT License.
