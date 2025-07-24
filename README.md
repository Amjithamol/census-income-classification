# 📊 Census Income Classification

A machine learning project using the UCI Adult dataset to classify whether an individual's income exceeds $50K per year.

## 📁 Table of Contents

- [About the Project](#about-the-project)
- [Dataset Information](#dataset-information)
- [Tools and Technologies](#tools-and-technologies)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Author](#author)

---

## 📌 About the Project

The objective is to build a classification model that predicts whether an individual's income is >50K or <=50K, using demographic and employment-related data. This is a common benchmark dataset for binary classification problems.

---

## 📂 Dataset Information

- *Source*: [UCI Machine Learning Repository - Adult Dataset](https://archive.ics.uci.edu/ml/datasets/census+income)
- *Attributes*: Age, Workclass, Education, Marital Status, Occupation, Relationship, Race, Sex, Capital Gain/Loss, Hours-per-week, etc.
- *Target Variable*: Income (Binary: >50K, <=50K)

---

## 🛠 Tools and Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

---

## 🔍 Data Preprocessing

- Handling missing values (? entries)
- Encoding categorical variables
  - Label Encoding
  - One-Hot Encoding
- Feature scaling
- Train-test split (80/20)

---

## 📈 Exploratory Data Analysis (EDA)

- Age and income distribution
- Correlation heatmaps
- Income by education and occupation
- Visualizations using barplots, histograms, and boxplots

---

## 🤖 Modeling

Trained and compared the following models:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XG boosting


---

## 📊 Evaluation Metrics

| Model               | Accuracy | Precision | Recall | F1‑Score |
|--------------------|:--------:|:---------:|:------:|:--------:|
| Logistic Regression|  81.2%   |  94.3 %   | 79.2%  |   86.2%  |
| Random Forest      |  84.3%   |  88.6%    | 81.3%  | 70.5%    |
| SVM                |  81.3%   |  95.4%    | 79.2%  |   86.5%  |
|XG boost            |  87.5%   |    90%    |   94%  |  91.9%   |
 

---

## 📝 Conclusion

The best performing model was * XG boost*, offering a good balance of accuracy and precision. The dataset required significant preprocessing due to class imbalance and categorical variables, but the models performed well overall.


## 👩‍💻 Author

*Amjitha Mol*  
[GitHub Profile](https://github.com/Amjithamol)


---

