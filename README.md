# Python Pandas World Population Exploratory Data Analysis
Analyses patterns in world population data for the last 50 years.

## Tools and technologies
- **Jupyter Notebook**
- **Python**:
  - pandas
  - numpy
  - seaborn
  - matplotlib

## Project Objectives
- Analyse patterns in the world population over the last 50 years

## Data Sources
- [World Population](world_population.csv)

## Analysis steps
- **Data Exploration**:
  - Imported libraries
  - Transformed the world population file to a dataframe
  - Formated each number to two decimal places
  - Showed columns non-null count and data type
  - Showed statistical elements for each column
  - Showed null values for each column
  - Showed unique values for each column
  - Showed columns by data type
  - Showed the top and bottom 10 values for the column 2022 population
  - Sorted dataframe descendingly by world population percentage
  - Showed the numerical correlation between columns using numpy
  - Showed the visual and numerical correlation between columns using seaborn and matplotlib
  - Showed the mean of each continent
  - Showed the mean of each continent, sorted by the 2022 population descendingly
  - Showed all countries in Oceania
  - Made a list of all column names
  - Made a new dataframe df2 showing the mean of each continent, sorted by the 2022 population descendingly and only including population data
  - Transpose the axes of df2 to show continents in the columns and populations in the rows
  - Showed a line plot of the growth of continents
  - Showed outliers by using a boxplot

## Key findings
- The Vatican City is the smallest country
- Population density varies widely, so in some countries people live very close together, while in others they live very far apart
- All continents populations have grown incrementally, except for Asia, which has exhibited explosive population growth

## Visualizations
**Heat map of the correlation between columns**

![Heatmap of the correlation between columns](heatmap_correlation_matrix_between_columns.png)

**Line plot of the growth of continents over time**

![Line plot of the growth of continents](line_plot_growth_of_continents.png)

**Boxplot of outliers across columns**

![Boxplot of outliers](box_plot_outliers.png)

## Conclusion
There is a big difference in population growth and density between Asia and the rest of the world. 
