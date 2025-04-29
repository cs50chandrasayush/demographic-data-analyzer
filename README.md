# demographic-data-analyzer
Performed demographic analysis on census data using Pandas. Calculated education, income, and work-hour trends by race, gender, and country using group operations and filtering.


# Demographic Data Analyzer

This project is part of the **freeCodeCamp Data Analysis with Python Certification**. It analyzes demographic data from the [1994 U.S. Census database](https://archive.ics.uci.edu/ml/datasets/adult) to extract meaningful insights such as education levels, work hours, income distribution, and more.

## 📁 Dataset

The dataset used is `adult.data.csv`, which contains information such as:
- Age
- Workclass
- Education
- Marital Status
- Occupation
- Race
- Sex
- Capital Gain/Loss
- Hours Worked per Week
- Native Country
- Salary (>50K or <=50K)

## 🛠️ Features Implemented

- ✅ Cleaned and preprocessed the dataset (e.g., removed missing values, trimmed whitespace).
- ✅ Replaced `?` values with `NaN` and filled missing categorical data with the mode.
- ✅ Counted each race category in the dataset.
- ✅ Calculated the **average age of men**.
- ✅ Found the **percentage of people with a Bachelor's degree**.
- ✅ Compared income levels of people with and without **advanced education** (Bachelors, Masters, Doctorate).
- ✅ Found the **minimum number of work hours per week** and determined what percent of those earn >50K.
- ✅ Identified the **country with the highest percentage of people earning >50K**.
- ✅ Determined the **most common occupation in India for people earning >50K**.

## 📊 Sample Output

Average age of men: 39.4
Percentage with Bachelors: 16.4%
Higher education rich: 46.5%
Lower education rich: 17.4%
Min work time: 1 hours/week
Percentage of rich among those who work fewest hours: 10.0%
Country with highest percentage of rich: Iran
Highest percentage of rich people in country: 41.9%
Top occupation in India for people earning >50K: Prof-specialty
