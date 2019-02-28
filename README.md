# Applied Machine Learning Workshop, 02/28/2019

Hi Everyone,

< Insert Image.>

This is the notebook from the [Columbia Data Science Society's](https://www.facebook.com/cdsscu/) Workshop on [**Applied Machine Learning**](https://www.facebook.com/events/247226822888651/).

**Presented by:** Akhil Punia, MS Data Science ( 2019 )

# Acknowledgement
The content of this talk is motivated from the two classes, I am taking this semester at Columbia Data Science Institute.

- [COMS W4995 Applied Machine Learning ](http://www.cs.columbia.edu/~amueller/comsw4995s19/schedule/) *taught by* Andread C. Müller, core contributer of sci-kit learn and author of the O'Reilly book "Introduction to machine learning with Python", describing a practical approach to machine learning with python and scikit-learn. 
- [COMS W4721 Machine Learning for Data Science](http://www.columbia.edu/~jwp2128/Teaching/W4721/Spring2019/W4721Spring2019.html) * taught by*
Prof. John Paisley. He also teaches a course on [**Machine Learning**](https://www.edx.org/course/machine-learning-columbiax-csmm-102x-0) through **edx**.The content of his on-campus course largely overlaps with his edx class.

## Basic Outline of the Notebook

#### 01 Dataset: House Prices Regression [70%]
  - 1.1 : EDA : 
    - Categorical 
    - Continous 
    - *Ordinal
  - 1.2 : Treat Missing Values
    - sklearn impute
    - encoding for missing values 
  - 1.3 : Outliers
  - 1.4 : Feature Engineering
    - Polynomial Featues
    - Label Encodings
#### 02 Models: [10%] 
  - 2.1 : Linear Regression: l1, l2, elastic net
  - 2.2 : Logistic Regression
  - 2.3 : Decision Trees
    - 2.3.1: Random Forest
    - 2.3.2: Bagging
    - 2.3.3: Gradient Boosting: xgboost ( others: lightgbm,  catboost)

#### 03 Model Evaluation and Improvement ( aka Parmeter Tuning ) [20%]
  - 3.1 : Metrics: Accuracy, Precision, Recall, F-Score , [ MAPE ( forecasting ) ]
  - 3.2 : Plots:  ROC, Confusion Matrix, Prediction Plots, Residual Plots, Residuals vs Features Plot
  - 3.3 : Hard Coded Optimization: GridSearch, RandomSearch
  - 3.4 : New Techniques: ( skopt, bayesian opt, hypreropt )

#### 04 Special Challenges: 
  - 4.1 Ovefitting
    - 4.1.1 : Train, Test, Valid
    - 4.1.2 : Regularisation
  - 4.2 : Class Imbalance: 
    - 4.2.1 : Problem Description
    - 4.2.2 : Possible Solutions ( Under and Over Sampling, Loss Fucntions )

**Q: What is better Type-I or Type II error ( a.k.a. False Positives and False Negatives ) ? **

#### 05 Model Explanability
  - Feature Importance  
  - Regression Coefficients
  - XGBoost Feature Importance
  - New Stuff: Impact of Individual Predictions
    - SHAP Values

#### 06 Resources
  - Kaggle: Regression Challenge ( House Prices )
  - Kaggle: Machine Learning Explainability
  - Categorical Data Plotting: https://seaborn.pydata.org/tutorial/categorical.html
  - Continous Data Plotting: https://seaborn.pydata.org/tutorial/distributions.html#plotting-univariate-distributions

#### 07 Quick Tips
  - Code Breaks: Library Version , pip/ conda upgrade -> virualenv
  - Visualising High Dimensional Data: Principal Component Analysis
