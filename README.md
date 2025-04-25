# EDA-and-Visualization-of-a-Real-World-Dataset
Performed exploratory data analysis on the Titanic dataset to clean data, handle missing values, and visualize key patterns. Used Pandas, Seaborn, and Matplotlib to generate insights on age distribution, survival rates, and feature correlations.

# EDA and Visualization on Titanic Dataset

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover insights and understand data distribution, relationships, and patterns using visualization techniques.

##  Dataset

The dataset used is the publicly available Titanic dataset from [Data Science Dojo's GitHub Repository](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

##  Key Steps Performed

- Loaded and explored the dataset using Pandas.
- Handled missing values:
  - Filled missing `Age` values with the median.
  - Filled missing `Embarked` values with the mode.
  - Dropped the `Cabin` column due to high missing rate.
- Removed duplicate records.
- Detected outliers using boxplots.
- Created various visualizations:
  - Count plot of survival.
  - Histogram of age distribution.
  - Correlation heatmap for numerical features.

## Tools & Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

##  Insights

- Most passengers were aged between 20 and 40.
- Younger passengers had higher survival rates.
- `Fare` showed a notable correlation with `Pclass`.
- Proper data cleaning improved the dataset quality for further analysis or model development.

