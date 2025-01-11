## Table of Contents
- [Project Description](#project-description)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description
This project aims to classify whether a passenger survived the Titanic disaster using their demographic and ticket information. The process includes:
1. Data loading and exploration.
2. Data preprocessing and feature engineering.
3. Model training and evaluation.
4. Interpretation of results.

## Data Source
The dataset is publicly available on [Kaggle](https://www.kaggle.com/c/titanic/data).

### Dataset Structure
- **train.csv**: Training dataset containing features and survival labels.
- **test.csv**: Test dataset for predictions.

## Methodology
1. **Exploratory Data Analysis (EDA):** Analyze data distributions and relationships.
2. **Preprocessing:** Handle missing values, encode categorical variables, and scale numerical features.
3. **Modeling:** Train classification models such as Logistic Regression, Decision Trees, and Random Forests.
4. **Evaluation:** Assess model performance using accuracy, precision, recall, and F1-score.

## Results
The feature importance analysis revealed that `Pclass`, `Sex`, and `Age` were the most significant predictors. 

