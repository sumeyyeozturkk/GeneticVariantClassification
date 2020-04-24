# Genetic Variant Classification
This is a Binary Classification project carried out in Applied Data Science Bootcamp on Kodluyoruz, which is realized under the trainings of Çağlar Subaşı, using the Genetic Variant Classification dataset in Kaggle.

[Dataset used in this project](https://www.kaggle.com/kevinarvai/clinvar-conflicting)

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is the objective is to predict whether a Clinic Variant will have conflicting classifications. This is presented here as a binary classification problem, where each record in the dataset is a genetic variant.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling


### Technologies
* Python
* Pandas, Numpy
* Matplotlib,Seaborn
* Missingno
* Sklearn

### Modelling Algorithms
* Logistic Regression
* XGBoost Classifier
* KNeighbors Classifier
* Decision Tree Classifier
* LigthGBM Classifier
* Gradient Boosting Classifier
* Hist Gradient Boosting Classifier

## Project Description
Clinic Variant is a public resource containing annotations about human genetic variants. These variants are (usually manually) classified by clinical laboratories on a categorical spectrum ranging from *benign, likely benign, uncertain significance, likely pathogenic, and pathogenic.* Variants that have conflicted classifications (from laboratory to laboratory) which can be confusing when clinicians or researchers try to interpret whether the variant has any impact of diseases on patients.

A classification is counted as conflicted when any couple (duo) of the following three categories are present for one variant, two submissions of one category are not considered as conflicted.

1. Likely Benign or Benign
2. VUS
3. Likely Pathogenic or Pathogenic

The conflicted classifications have been assigned to the column called `CLASS`. This is a binary representation of whether a variant has conflicted classifications, where `0` represents consistent classifications and `1` represents conflicted classifications.

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://www.kaggle.com/kevinarvai/clinvar-conflicting) also within this repo.


#### Members:

|Name     |
|---------|
|[Sümeyye ÖZTÜRK](https://github.com/sumeyyeozturkk)
|[Mehmet Haliloğlu](https://github.com/mehmethaliloglu)
|[Mert Yıldırır](https://github.com/mertyldrr)
