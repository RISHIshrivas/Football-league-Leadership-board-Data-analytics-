# Football-league-Leadership-board-Data-analytics
This Python script analyzes the performance of football players based on various statistics. The dataset includes information such as matches played, goals scored, expected goals (xG), shots, and more. The analysis involves data cleaning, exploration, and visualization.

# Prerequisites
Make sure you have the following libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- google.colab (for Colab environment)
# You can install the required libraries using:
pip install pandas numpy matplotlib seaborn statsmodels google-colab

# Instructions
- Run the provided code in a Jupyter Notebook or a similar environment.
- Ensure you have the required dataset named "Data.csv" or adjust the file name accordingly.
# Code Structure
- Data Loading and Exploration: The script loads the dataset, inspects its structure using info() and head(), and checks for any duplicate or missing values.

- Data Cleaning: It handles column names, drops duplicates, and ensures there are no missing values.

- Descriptive Statistics: Provides descriptive statistics for numerical columns like matches played, goals, shots, and on-target shots.

- Data Visualization: Uses seaborn and matplotlib for creating histograms and boxplots to visualize the distribution and spread of key performance indicators.

- Outlier Removal: Identifies and removes outliers using the IQR method for matches played, goals, shots, and on-target shots.

- Categorical Data Mapping: Maps numerical codes to meaningful names for 'League' and 'Country' columns.

- One-Hot Encoding: Converts categorical variables into dummy/indicator variables.

- Skewness Check: Evaluates skewness in numerical columns.

- Pair Plots: Utilizes pair plots for exploring relationships between different performance metrics.

- Count Plot: Displays a count plot for the 'OnTarget' variable.

# License
This code is provided under the MIT License. Feel free to use, modify, and distribute it.
