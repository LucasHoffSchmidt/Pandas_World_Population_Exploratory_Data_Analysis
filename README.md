# Pandas World Population Exploratory Data Analysis
In this project we used pandas to analyse patterns in world population data over the last 50 years.

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
- Loaded the world population dataset into a dataframe
<img src = "images/dataframe.jpg" alt="World population dataframe" width="1000">

- Formatted each number to two decimal places using set_option().
<img src = "images/format.jpg" alt="Displaying each float in the dataset with 2 decimals" width="500">

- Checked nulls and data types of columns
<img src = "images/info.jpg" alt="Checking nulls and data types of columns" width="450">

- Got an overview of the statistical distribution of the numerical columns of the dataframe
<img src = "images/describe.jpg" alt="Statistical distribution of numerical columns" width="900">

- Inspected count of nulls for each column
<img src = "images/absolute_nulls.jpg" alt="Absolute nulls for each column" width="400">

- Found number of unique values for each column
<img src = "images/nunique.jpg" alt="Number of unique values for each column" width="400">

- Got an overview of the columns in the dataset
<img src = "images/column_names.jpg" alt="Column names of the dataframe" width="600">

- Filtered numerical columns
<img src = "images/num_columns.jpg" alt="Filtering numerical columns of the dataframe" width="1000">

- Showed top 10 lowest populations in 2022
<img src = "images/low_2022.jpg" alt="Top 10 lowest populations in 2022" width="600">

- Showed top 10 highest populations in 2022
<img src = "images/high_2022.jpg" alt="Top 10 highest populations in 2022" width="650">

- Made an overview of the correlation between numerical columns
<img src = "images/num_columns.jpg" alt="Correlation between numerical columns" width="1000">

- Created a heatmap of the correlation between numerical columns
<img src = "images/heatmap.jpg" alt="Heatmap over correlations between numerical columns" width="1000">

- Showed the mean of each continent, sorted descendingly by the population in 2022
<img src = "images/mean_cont.jpg" alt="Mean of continents sorted descendingly by 2022 population" width="800">

- Listed all countries in Oceania
<img src = "images/oceania.jpg" alt="Population counts for countries in Oceania" width="700">

- Calculated the mean of each continent, sorted by the 2022 population descendingly, and only including population data
<img src = "images/mean_cont_pop_data.jpg" alt="" width="1000">

- Transposed dataframe to have continents for columns and populations for rows
<img src = "images/transpose.jpg" alt="Transposing dataframe" width="700">

- Created a lineplot of population growth over time by continent
<img src = "images/line_plot.jpg" alt="Population growth over time by continent" width="1000">

- Created a boxplot of Distribution of population count by year
<img src = "images/boxplot.jpg" alt="Distribution of population count by year" width="1000">

## Key findings
- The Vatican City is the smallest country.
- Population density varies widely by country.
- All continents populations have increased linearly, except for Europe, whose population has decreased and Asia, which exhibited explosive population growth in the 1990s, followed by linear growth.
- China and India are by far the greatest contributors to the growth in Asia, with almost 3 billion people between them in 2022. 
