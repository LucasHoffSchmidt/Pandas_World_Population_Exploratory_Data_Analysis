# Pandas World Population Exploratory Data Analysis
In this project we used pandas to analyse patterns in world population data over the last 50 years to determine the growth rate of the world population.

## Quick Links
- World population dataset: [World Population Dataset](world_population.csv)
- Jupyter notebook of exploratory data analysis of the world population dataset. [Jupyter Notebook](world_population_data_exploration_project.ipynb)
- Other projects I have made: [Portfolio Website](https://lucashoffschmidt.github.io/)

## Technologies Used
- **Jupyter Notebook**: Web-based interactive computing environment. 
- **Pandas**: Dataset interaction and transformations. 
- **Matplotlib**: Data visualizations and formatting. 
- **Seaborn**: Statistical data visualizations. 

## Process
- Created a new Jupyter Notebook and imported pandas, seaborn and matplotlib.pyplot.
- Loaded the world population dataset into a dataframe with read_csv().
- Formatted each number to two decimal places using set_option().
- Used info(), describe(), isnull().sum() and nunique() to get an overview of the columns null values, data types, statistical distribution and unique values.
- Filtered numeric columns using select_dtypes().
- Used sort_values().head() to get the top and bottom values of the 2022 population, as well as the countries with the highest world population percentage. 
- Calculated and visualized numerical correlations by using corr() and heatmap().
- Used groupby(), mean() and sort_values() to get the mean of each continent, sorted by the 2022 population descendingly.
- Filtered Oceania countries with str.contains().
- Listed all column names with .columns.
- Created a new dataframe with population means of continents, sorted and transposed with transpose() to show continents in the columns and populations in the rows. 
- Plotted population growth using plot(). 
- Detected outliers with boxplot().

## Key findings
- The Vatican City is the smallest country.
- Population density varies widely by country.
- All continents populations have increased linearly, except for Europa, which population has decreased and Asia, which exhibited explosive population growth in the 1990s, followed by linear growth.
- China and India are by far the greatest contributors to the growth in Asia with almost 3 billion people between them in 2022. 

## Visualizations
**Heat map of the correlation between columns**

![Heatmap of the correlation between columns](heatmap_correlation_matrix_between_columns.png)

**Line plot of the growth of continents over time**

![Line plot of the growth of continents](line_plot_growth_of_continents.png)

**Boxplot of outliers across columns**

![Boxplot of outliers](box_plot_outliers.png)

## Conclusion
All continents' populations seem to be growing linearly, except for Europe which has a decreasing population and Asia which had an explosive population growth in the 1990s and is now growing linearly.
The greatest contributors to the population growth worldwide is by far China and India with almost 3 billion people between them in 2022. 
