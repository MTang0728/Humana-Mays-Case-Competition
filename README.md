# Humana Mays Case Competition 2020

## About the Competition:
[Competition Details](https://mays.tamu.edu/humana-tamu-analytics/)

## Intro:
With the rapid pace of social development, we humans have enjoyed an easier way of living and commuting. Meanwhile, we are exposed to a growing number of health-threatening substances and sites, which makes it harder for the medicare industry to evaluate health and its cost. Fortunately, the introduction of Humana’s integrated value-based health ecosystem based on Social Determinants of Health brings a promising prospect to this industry. Among all those challenges to health, transportation challenge stands out to be the most common one since it involves daily life of a person’s commuting, schooling, and living. The pain point lies in the aspect of prediction and optimal choices of model fitting. With a large amount of robust data provided by Humana, this analysis identifies MediCare members who are most likely to experience Transportation Challenges and propose viable solutions. This analysis is intended to find the interconnection between our socio-economic and community environments and lifestyle behaviours, based on which employees, patients, clients are better medically assisted.

For a detailed analysis, please refer to the [report](./Doc/Report.pdf).

**-- Project Status: [Completed]**

**-- Competition Status: [Top 50 teams]**

## Methods Used:
- Exploratory Data Analysis (EDA)
- Missing value imputation
- Categorical variable encoding
- Feature engineering
- Hyperparameter tunning

## Models Used:
- Logistic Regression Classifier
- Random Forest Classifier
- XGBoost Classifier

## Model Performance Comparison:
Model | Average AUC 
------| -----------
Logistic Regression Classifier | 0.739
Random Forest Classifier | 0.720
XGBoost Classifier | 0.736

The values presented above are calculated using 10-folds cross-validation on the training set.

## Tools/Packages Used:
### Tools:
- R for preliminary data inspection
- Interactive Python in Jupyter Notebook

### Packages:
- **Pandas** for data wrangling and manipulation
- **NumPy** for arithmetic operation
- **matplotlib** for data visualization
- **Category Encoders** for encoding categorical variables
- **scikit-learn** for building Random Forest & Logistic Regression classifiers, selecting features, tunning hyperparameters and evaluating performance
- **XGBoost** for building XGBoost classier

## Project Member:
- Yicheng Huang: [@Yicheng Huang](https://github.com/yichenghuang980)
- Michael Tang: [@Michael Tang](https://github.com/MTang0728)
- Shangwen Yan: [@Shangwen Yan](https://github.com/shangwenyan)
