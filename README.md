# 💳 Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Machine Learning](https://img.shields.io/badge/ML-Fraud%20Detection-green.svg)

## 📋 Overview

An intelligent machine learning system designed to identify and prevent fraudulent credit card transactions. This project implements advanced algorithms to analyze transaction patterns and distinguish between legitimate and fraudulent activities, enhancing security and reducing financial losses.

## 🎯 Objectives

- **Detect Fraud**: Identify fraudulent transactions with high accuracy
- **Minimize False Positives**: Reduce legitimate transactions being flagged as fraud
- **Real-time Analysis**: Enable quick decision-making for transaction approval
- **Financial Protection**: Safeguard consumers and financial institutions from losses

## 📁 Project Structure

```
Credit_Card_FraudDetection/
│
├── main.ipynb              # Main Jupyter notebook with analysis and models
├── creditcard.csv          # Dataset containing transaction records
├── BDA_Final_Report.pdf    # Comprehensive project report
├── .gitattributes          # Git configuration file
└── README.md               # Project documentation
```

## 🔍 Features

- **Exploratory Data Analysis (EDA)**: Comprehensive analysis of transaction patterns
- **Data Preprocessing**: Handling imbalanced datasets and feature engineering
- **Machine Learning Models**: Implementation of multiple classification algorithms
- **Performance Metrics**: Evaluation using precision, recall, F1-score, and ROC-AUC
- **Visualization**: Clear graphical representations of data insights

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Jupyter Notebook**: Interactive development environment
- **Machine Learning Libraries**: 
  - Scikit-learn
  - Pandas
  - NumPy
- **Visualization**: Matplotlib, Seaborn

## 📊 Dataset

The project uses a credit card transaction dataset (`creditcard.csv`) containing:
- Transaction features (anonymized for privacy)
- Transaction amounts
- Time stamps
- Class labels (legitimate vs. fraudulent)

**Note**: The dataset is highly imbalanced, with fraudulent transactions representing a small percentage of total transactions, making this a challenging classification problem.

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.x
Jupyter Notebook
Required libraries (install via pip)
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Prem-CyberSec/Credit_Card_FraudDetection.git
cd Credit_Card_FraudDetection
```

2. Install required packages:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook main.ipynb
```

## 📈 Model Performance

The project implements and compares multiple machine learning algorithms to achieve optimal fraud detection performance. Key metrics include:
- **Accuracy**: Overall correctness of predictions
- **Precision**: Ratio of correct fraud predictions
- **Recall**: Ability to identify all fraudulent transactions
- **F1-Score**: Harmonic mean of precision and recall
- **ROC-AUC**: Model's ability to distinguish between classes

## 📄 Documentation

For detailed analysis, methodology, and results, please refer to the [BDA_Final_Report.pdf](BDA_Final_Report.pdf) included in the repository.

## 🤝 Contributing

This repository is archived and not accepting contributions at this time.

## 👤 Author

**Prem-CyberSec**
- GitHub: [@Prem-CyberSec](https://github.com/Prem-CyberSec)

## 📝 License

This project is available for educational and reference purposes.

## ⚠️ Disclaimer

This project is for educational purposes only. The dataset and models should not be used in production environments without proper validation and compliance with financial regulations.

---

**Note**: This repository is currently archived. For any inquiries, please contact the repository owner.
```