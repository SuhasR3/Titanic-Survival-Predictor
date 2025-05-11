# Titanic Survival Predictor

![](https://github.com/SuhasR3/Titanic-Survival-Predictor/blob/main/dataset/banner.png)

![Python](https://img.shields.io/badge/python-3.8-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

A data science project exploring survival predictions on the Titanic dataset using machine learning techniques.

## Overview
This project analyzes the famous Titanic dataset to predict passenger survival using data preprocessing, visualization, and machine learning models. Built as part of a Kaggle challenge, it showcases practical data science workflows and insights into what factors influenced survival aboard the RMS Titanic.

## Features
- Data cleaning and preprocessing
- Exploratory data analysis (EDA) with visualizations
- The Custom preprocess_data function handles missing values, engineering features (e.g., titles, family size), scaling, and generating polynomial features.
- Machine learning models (Decision Tree, Logistic Regression, Random Forest, K-Nearest-Neighbors, Linear SVC, Support Vector Machine, Stochastic Gradient Descent, Perceptron, Naive Bayes)
- Performance evaluation and insights

## Getting Started
### Prerequisites
- Python 3.8
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn` (see `requirements.txt`)

### Installation
1. Clone the repository:
```
   git clone https://github.com/SuhasR3/TitanicDataDive.git
   ```
2. Install dependencies:
```
  pip install -r requirements.txt
```
3. Download the dataset from [Kaggle](https://www.kaggle.com/competitions/titanic) and place it in the `Dataset/` folder.

### Usage
Open `titanic_data_solutions.ipynb` in Jupyter Notebook or Google Colab to run the analysis step-by-step.

## Results
Resulting Decision Tree is as follows

![](https://github.com/SuhasR3/Titanic-Survival-Predictor/blob/main/dataset/DT.png)

Achieved the following accuracy values.

![](https://github.com/SuhasR3/Titanic-Survival-Predictor/blob/main/dataset/Titanic_Survival_Predictor_Output.png)
  
Key findings: "Women and children had higher survival rates & Pclass was a strong predictor."


## Acknowledgments
- Dataset provided by [Kaggle](https://www.kaggle.com/c/titanic).

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/SuhasR3/Titanic-Survival-Predictor/blob/main/LICENSE.md) file for details.   
