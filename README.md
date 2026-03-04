# Boston Housing Data Analysis

## Project Overview

This project analyzes the **Boston Housing dataset** to explore factors that influence housing prices.
The analysis includes data visualization, statistical hypothesis testing, correlation analysis, and regression modeling using Python.

The goal of this project is to understand how different variables affect the **median value of owner-occupied homes (MEDV)**.

---

## Dataset

The dataset used in this project is the **Boston Housing Dataset** which contains information collected by the U.S Census Service concerning housing in the Boston area.

Important variables in the dataset include:

* **MEDV** – Median value of owner-occupied homes
* **CHAS** – Charles River dummy variable (1 if tract bounds river, 0 otherwise)
* **AGE** – Proportion of owner-occupied units built prior to 1940
* **NOX** – Nitric oxide concentration
* **INDUS** – Proportion of non-retail business acres per town
* **PTRATIO** – Pupil-teacher ratio by town
* **DIS** – Weighted distances to five Boston employment centers

---

## Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* SciPy
* Statsmodels
* Jupyter Notebook

---

## Data Visualization

The project includes several visualizations to better understand the dataset.

**Box Plot**

* Used to analyze the distribution of median home values.

**Bar Plot**

* Shows the number of houses near the Charles River.

**Box Plot by Age**

* Compares housing prices across different age groups of houses.

**Scatter Plot**

* Shows the relationship between Nitric Oxide concentration (NOX) and industrial areas (INDUS).

**Histogram**

* Displays the distribution of the pupil-teacher ratio (PTRATIO).

---

## Statistical Analysis

Several statistical tests were performed in this project:

**Independent T-Test**

* To determine whether houses near the Charles River have different median values compared to houses not near the river.

**ANOVA Test**

* To check whether there are significant differences in housing prices among different age groups.

**Pearson Correlation**

* To examine the relationship between nitric oxide concentration (NOX) and industrial areas (INDUS).

**Linear Regression**

* To analyze the relationship between distance to employment centers (DIS) and median house value (MEDV).

---

## Key Insights

* Environmental and structural factors influence housing prices.
* Statistical testing helps determine significant relationships between variables.
* Industrial areas and pollution levels show correlation.
* Regression analysis helps understand how distance from employment centers affects housing values.

---

## Author

Virajbhai Vinubhai Mavani

This project was completed as part of the **IBM Data Science Professional Certificate** on Coursera.
