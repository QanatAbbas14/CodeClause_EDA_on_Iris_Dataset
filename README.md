# Iris Dataset Analysis & Visualization

This repository contains the code and visualizations for analyzing the Iris dataset as part of my internship at CodeClause. The project aims to explore the dataset through various data visualization techniques, helping to understand the relationships and patterns within the data.

## Project Overview

The Iris dataset is one of the most famous datasets used in machine learning and statistics. It consists of 150 samples of iris flowers, with four features measured for each sample:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The dataset is divided into three classes, each representing a different species of iris flowers:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## Key Components

1. **Data Loading & Exploration**:
   - Loaded the dataset using Pandas and explored its structure.
   - Renamed columns for clarity and dropped the 'Id' column as it didn't contribute to the analysis.
   - Checked for missing values and obtained descriptive statistics.

2. **Pairplot Visualization**:
   - Used Seaborn's pairplot to visualize the pairwise relationships between the features, color-coded by species.

3. **Correlation Heatmap**:
   - Generated a heatmap to visualize the correlation between different features, helping to identify strong relationships.

4. **Distribution Plots**:
   - Created distribution plots for each feature to understand the distribution of data across different species.

5. **FacetGrid Distribution Plots**:
   - Used Seaborn's FacetGrid to create distribution plots for each feature, separated by species.

6. **Boxplots**:
   - Plotted boxplots to visualize the spread and outliers in the data for each feature across different species.

7. **Violin Plots**:
   - Created violin plots to combine boxplots and density plots, providing a more detailed view of the data distribution.

## Installation

To run this project locally, you'll need Python 3.x and the following libraries:
- Pandas
- NumPy
- Seaborn
- Matplotlib

You can install the required libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib
