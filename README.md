# Student-Result-Analysis
The project focuses on exploring and visualizing various aspects of student performance, including factors like gender, parental education, marital status, and ethnic group



## Contents

- [Getting Started](#getting-started)
- [Data Overview](#data-overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Outlier Detection](#outlier-detection)
- [Ethnic Group Distribution](#ethnic-group-distribution)
- [Numerical Column Distribution](#numerical-column-distribution)
- [Contributing](#contributing)

## Getting Started

To run the analysis, you'll need the following libraries:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

You'll also need to load the dataset, which should be stored in a CSV file named "Expanded_data_with_more_features.csv."

## Data Overview

This dataset includes key attributes such as gender, ethnic group, parental education, and lunch type, along with essential factors like test preparation, parental marital status, and sports participation. What makes this project truly engaging is the inclusion of students' scores in math, reading, and writing. By analyzing these variables, I aimed to uncover trends and patterns that could influence academic performance and student well-being. This project not only enhances our understanding of student dynamics but also highlights the importance of various socio-economic factors in education.

## Data Cleaning

The analysis kicks off with a crucial data cleaning process to ensure the dataset is ready for insightful analysis. First, I identify and eliminate unnecessary columns, including the "Unnamed: 0" column, which serves no analytical purpose. Next, I tackle missing values across multiple columns, employing strategies like imputation or removal, depending on the context and impact on the dataset's integrity. This step is vital as it enhances data quality, ensuring that the analysis yields accurate and reliable results. By meticulously cleaning the data, I lay a strong foundation for subsequent analyses, allowing for clearer insights into the factors influencing student performance and overall educational outcomes.

## Exploratory Data Analysis

- Gender Distribution: Visualizes the distribution of students by gender.
- Parental Education: Analyzes the relationship between students' scores and their parents' education levels.
- Parental Marital Status: Examines the correlation between students' scores and their parents' marital status.

## Outlier Detection

To identify outliers in the math, reading, and writing scores, I utilized box plots. This visual tool highlights data points that fall outside the interquartile range, allowing for easy detection of anomalies. Understanding these outliers is crucial for refining analyses and interpreting student performance accurately.

## Ethnic Group Distribution

- Calculates the number of students in each ethnic group (Group A, Group B, Group C, Group D, Group E).
- Visualizes the distribution of students in different ethnic groups using a pie chart and bar plot.

## Numerical Column Distribution

Visualizes the distribution of numerical columns (math score, reading score, writing score) using violin plots.

## Contributing

Contributions and feedback are welcome. If you have ideas for improving the analysis or adding new features, feel free to create pull requests or open issues.
