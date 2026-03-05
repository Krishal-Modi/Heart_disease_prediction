# Heart Disease Prediction

A machine learning project that predicts whether a patient has heart disease based on their medical attributes using various classification algorithms.

## 📋 Project Overview

This project uses Python-based machine learning libraries to build a predictive model capable of determining whether a patient has heart disease. The analysis follows a structured approach from problem definition through to model experimentation.

## 🎯 Problem Statement

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

**Success Metric**: Achieve 95% accuracy in predicting heart disease during the proof of concept phase.

## 📊 Dataset

The dataset originates from the Cleveland data from the UCI Machine Learning Repository:
- **Source**: [UCI Machine Learning Repository - Heart Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Alternative**: [Kaggle - Heart Disease Classification Dataset](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset)

### Features

The dataset includes 14 medical attributes:

1. **age** - Age in years
2. **sex** - Sex (1 = male; 0 = female)
3. **cp** - Chest pain type (0-3)
4. **trestbps** - Resting blood pressure (mm Hg)
5. **chol** - Serum cholesterol (mg/dl)
6. **fbs** - Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. **restecg** - Resting electrocardiographic results (0-2)
8. **thalach** - Maximum heart rate achieved
9. **exang** - Exercise induced angina (1 = yes; 0 = no)
10. **oldpeak** - ST depression induced by exercise
11. **slope** - Slope of peak exercise ST segment (0-2)
12. **ca** - Number of major vessels colored by fluoroscopy (0-3)
13. **thal** - Thalium stress test result
14. **target** - Heart disease present (1 = yes, 0 = no)

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest Classifier

## 📁 Project Structure

```
Heart_disease_prediction/
│
├── end-to-end-heart-disease-classification.ipynb  # Main analysis notebook
├── heart-disease.csv                               # Dataset
├── README.md                                       # Project documentation
└── LICENSE                                         # MIT License
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Krishal-Modi/Heart_disease_prediction.git
cd Heart_disease_prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook end-to-end-heart-disease-classification.ipynb
```

## 📈 Methodology

1. **Problem Definition** - Define the prediction goal
2. **Data Analysis** - Explore and understand the dataset
3. **Evaluation Metrics** - Define success criteria
4. **Feature Engineering** - Understand feature importance
5. **Modeling** - Train multiple classification models
6. **Experimentation** - Hyperparameter tuning and optimization

## 🔍 Model Evaluation

The project evaluates models using:
- Cross-validation scores
- Confusion matrix
- Precision, Recall, and F1-Score
- Classification reports

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

Krishal Modi

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## ⭐ Show your support

Give a ⭐️ if this project helped you!