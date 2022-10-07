# Classifying Employee Attrition

The project aims to identify the main contributing factors leading to employee attrition and determine the attrition likelihood based on the employee's profile.
---
Dataset: Kagle ["HR Analytics"](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction)

## Key findings

The results show that employee profiles – considering personal and professional factors – carry predictive power to determine the attrition likelihood.

### What are the top five most impactful work attributes that increase the changes of attrition?

- Work overtime
- Travel frequently
- Technical and sales roles
- Being single
- Lack of job promotion

### What are the most frequent departments, education fields, and job roles that experience attrition?

- Department: Sales
- Education Field: Technical degree
- Job Role: Sales representative

### What's the best performing model?

Logistic regression showed the best values of *accuracy* and *f1-score*:
- Test set:
  - Accuracy: 0.88
  - F1-score: 0.53

## Installation

The [requirements.txt](./requirements.txt) file contains the libraries needed for the project:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

The following commands create a virtual environment with these libraries:
```bash
git clone <repo>
cd <repo>
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Then, everything should be ready to run the main notebook:
```bash
code HR-Employee-Attrition.ipynb
```

## File descriptions

- [HR-Employee-Attrition.ipynb](HR-Employee-Attrition.ipynb): This is the main notebook that contains the end-to-end machine learning process. It includes: 
  - Data exploration
  - Data preparation
  - Modelling
  - Fine-tuning
  - Result interpretations
- [requirements.txt](requirements.txt): Project dependencies
