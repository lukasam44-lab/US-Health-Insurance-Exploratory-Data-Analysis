A short exploratory data analysis (EDA) of a US health insurance dataset, using Python to examine the relationships between variables such as age, sex, BMI, number of children, smoking status, region, and insurance charges.

📌 Overview

This project explores how the different features in the dataset relate to one another. The main goal was to understand the general relationships between all variables — identifying which features move together and how they connect to insurance charges — using correlation analysis and visualization.

🛠️ Tools & Libraries


Python
Pandas — data loading and cleaning
Seaborn & Matplotlib — data visualization
NumPy — numerical operations
Jupyter Notebook — analysis environment


📂 Dataset

The dataset (insurance.csv) contains the following columns:

ColumnDescriptionageAge of the individualsexGenderbmiBody Mass IndexchildrenNumber of dependentssmokerWhether the person smokesregionRegion in the USchargesInsurance charges billed

🔍 Analysis Steps


Data loading — imported the dataset with Pandas
Data inspection — checked for missing values and reviewed value distributions
Correlation analysis — examined how the numerical variables relate to each other
Visualization — built a Seaborn pairplot to visualize relationships across all variables at once


📈 Key Visualizations


Correlation analysis — measuring how strongly the numerical variables move together
Seaborn pairplot — a grid of scatter plots and distributions showing the relationships between every pair of variables in a single view

📝 Key Takeaways

This project practices core EDA skills — inspecting data, running correlation analysis, and using a pairplot to quickly spot relationships between many variables at once. It's a compact example of how visualization can reveal patterns in a dataset before any deeper modeling.

