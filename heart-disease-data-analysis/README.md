# Heart Disease Exploratory Data Analysis

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of a Heart Disease dataset using Python. The analysis focuses on understanding the structure and quality of the dataset, exploring demographic and clinical characteristics, and identifying patterns and associations between selected features and heart disease status.

## Objectives

The main objectives of this project are to:

* Understand the structure and characteristics of the dataset
* Assess data quality and identify duplicate records
* Explore the distribution of numerical and categorical features
* Analyze demographic characteristics such as age and sex
* Investigate the relationship between clinical features and heart disease status
* Examine relationships between continuous variables
* Identify potential outliers
* Summarize the main findings from the exploratory analysis

## Dataset

The dataset contains information about **303 patients** and includes demographic, clinical, and diagnostic features related to heart disease.

The `target` variable indicates heart disease status:

* `0` = No disease
* `1` = Presence of disease

### Feature Description

| Feature    | Description                                    |
| ---------- | ---------------------------------------------- |
| `age`      | Age of the patient                             |
| `sex`      | Sex of the patient                             |
| `cp`       | Chest pain type                                |
| `trestbps` | Resting blood pressure                         |
| `chol`     | Serum cholesterol                              |
| `fbs`      | Fasting blood sugar                            |
| `restecg`  | Resting electrocardiographic results           |
| `thalach`  | Maximum heart rate achieved                    |
| `exang`    | Exercise-induced angina                        |
| `oldpeak`  | ST depression induced by exercise              |
| `slope`    | Slope of the peak exercise ST segment          |
| `ca`       | Number of major vessels colored by fluoroscopy |
| `thal`     | Thalium stress test result                     |
| `target`   | Heart disease status                           |

Categorical variables are encoded numerically according to the dataset documentation and are interpreted using their corresponding feature definitions during the analysis.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* VS Code

## Analysis Workflow

1. Load and inspect the dataset
2. Examine the dataset structure and descriptive statistics
3. Review feature values and data types
4. Assess missing values and duplicate records
5. Remove duplicate observations
6. Explore distributions of continuous variables
7. Analyze demographic characteristics
8. Investigate clinical features in relation to heart disease status
9. Examine relationships between continuous variables
10. Identify potential outliers
11. Analyze correlations between continuous features
12. Summarize key findings and conclusions

## Data Quality

The dataset was reviewed for missing values, inconsistent categorical values, duplicate records, and potential outliers.

One duplicate record was identified and removed before the main exploratory analysis.

A potential outlier was observed in the `chol` feature, where one observation had a cholesterol value of `564 mg/dl`. The observation was retained because its magnitude alone was not sufficient evidence that it was an erroneous record.

## Exploratory Analysis

The analysis includes visualizations covering:

* Heart disease distribution
* Age distribution by sex
* Heart disease distribution by sex
* Age distribution by heart disease status
* Chest pain type and heart disease status
* Thalium stress test results and heart disease status
* Cholesterol and resting blood pressure
* Age and `oldpeak`
* Number of major vessels and heart disease status
* Correlations between continuous variables

The visualizations are used to explore patterns and associations within the observed sample.

## Key Findings

Several patterns were observed during the analysis:

* The dataset contains relatively similar numbers of participants with and without heart disease, although the heart disease group is slightly larger.
* The proportion of participants with heart disease differs between males and females in this dataset.
* The age distributions of participants with and without heart disease show substantial overlap.
* Differences can be observed in the distribution of chest pain types between the heart disease and no-disease groups.
* Thalium stress test results show different distributions between participants with and without heart disease.
* The number of major vessels observed through fluoroscopy shows an association with heart disease status in the dataset.
* Age and maximum heart rate (`thalach`) show a noticeable negative correlation.
* A potential outlier was identified in the cholesterol variable.

These findings describe patterns within the analyzed dataset and should not be interpreted as causal relationships.

## Conclusion

This exploratory analysis provided an overview of the structure, quality, distributions, and relationships within the Heart Disease dataset.

The analysis identified several differences in demographic and clinical features between participants with and without heart disease. Features such as chest pain type, thalium stress test results, and the number of major vessels showed noticeable differences across the two groups, while continuous variables revealed additional relationships through distribution and correlation analysis.

The findings represent associations observed within this specific dataset and do not establish causation or generalize to the broader population.

Further analysis could build on these findings through statistical testing and predictive modeling.

## Project Structure

```text
heart-disease-data-analysis/
│
├── data/
│   └── heart.csv
│
├── notebook/
│   └── heart-disease-data-analysis.ipynb
│
└── README.md
```

## Author

**Fatemeh Yousefi Amiri**

Data / Business Analyst | Python | SQL | Tableau

