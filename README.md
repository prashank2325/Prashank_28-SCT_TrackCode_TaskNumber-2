# Prashank_28-SCT_TrackCode_TaskNumber-2
# Titanic Dataset Analysis

This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The analysis explores relationships between variables and identifies patterns and trends in the data.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Insights](#key-insights)
- [Requirements](#requirements)
- [How to Run](#how-to-run)

## Introduction
The Titanic dataset contains data about the passengers on the Titanic, including their survival status, demographic information, and ticket details. This analysis aims to uncover insights regarding survival rates and the factors that influenced them.

## Dataset
The dataset used in this project is the Titanic dataset, which can be obtained from [Kaggle](https://www.kaggle.com/c/titanic/data). The data file used in this project is located in the project directory:
D:\Intership projects\titanic.csv



## Data Cleaning
The data cleaning process includes:
- Filling missing age values with the median age.
- Filling missing cabin values with 'Unknown'.
- Filling missing embarkation port values with the most common port (mode).

## Exploratory Data Analysis
The analysis includes:
1. **Summary Statistics**: Overview of numeric columns.
2. **Missing Data Visualization**: A heatmap to visualize missing values.
3. **Survival Rate**: Count of survivors and non-survivors.
4. **Survival Rate by Gender**: Analysis of survival rates based on gender.
5. **Survival Rate by Passenger Class**: Examination of survival rates across different passenger classes.
6. **Age Distribution**: Visualization of age distribution of passengers.
7. **Survival Rate by Embarkation Port**: Analysis of survival rates based on embarkation ports.
8. **Correlation Matrix**: A heatmap showing the correlation between numeric features.

## Key Insights
- Females had a much higher survival rate than males.
- Passengers in higher classes had better survival rates.
- Younger passengers had a higher likelihood of survival.
- Passengers who embarked from different ports had varying survival rates.

## Requirements
To run the analysis, you'll need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
How to Run
Clone this repository to your local machine.
Make sure to update the file path in the code to point to your local Titanic CSV file.
Run the Jupyter Notebook or Python script to perform data cleaning and EDA.
bash
Copy code
# To run the Python script
python titanic_analysis.py
License
This project is licensed under the MIT License.

vbn

### How to Use This README
1. Create a new file named `README.md` in the root directory of your GitHub repository.
2. Copy and paste the above content into the `README.md` file.
3. Adjust any sections to better fit your project or personal style.

This README provides a comprehensive overview of your project, guiding users
