
# World CO2 Emission Dashboard




## Overview

This project involves analyzing global CO2 emissions and creating an interactive dashboard using the Panel library in Python. The dashboard provides insights into CO2 emissions by continent, CO2 emissions over time, comparisons with GDP, and an analysis of emissions based on source type.
## Project Description

### Objective

The primary objective of this project is to visualize CO2 emission data effectively to gain insights into global patterns, trends, and relationships with economic factors like GDP. The dashboard allows users to interact with the data by selecting specific years, regions, and emission measures.

### Dataset


The analysis is based on the dataset sourced from [Our World in Data's CO2 dataset](https://raw.githubusercontent.com/owid/co2-data/master/owid-co2-data.csv), which includes information on CO2 emissions across various countries and continents over time.

### Tools and Libraries

- Pandas: For data manipulation and preprocessing.
- NumPy: For numerical operations.
- Panel: For building the interactive dashboard.
- hvPlot: For high-level plotting based on the PyData ecosystem.
- Tabulator: For creating interactive tables within the dashboard.

### Steps in the Analysis

**1.** Data Preprocessing: Handling missing data and creating necessary derived columns like GDP per capita.

**2.** CO2 Emission Over Time by Continent: Visualizing CO2 emissions across continents over time using line plots.

**3.** Creating Table for CO2 Emission: Displaying CO2 emission data in an interactive, paginated table.

**4.** CO2 vs GDP Scatterplot: Exploring the relationship between CO2 emissions and GDP per capita.

**5.** Bar Chart with CO2 Sources by Continent: Analyzing the sources of CO2 emissions across different continents.

**6.** Creating the Final Dashboard: Combining all elements into a cohesive dashboard using the Panel template.

### Key Features of the Dashboard

- Interactive Year Slider: Users can select the year of interest to update the visualizations dynamically.
- CO2 Emission Measure Selection: Radio buttons allow users to switch between different CO2 measures (e.g., total emissions, emissions per capita).
- Data Table: An interactive table that allows users to explore the data in a structured format.
- Scatterplot Analysis: Visualizing the relationship between GDP per capita and CO2 emissions.
- Bar Chart: Displaying the contribution of different sources (like coal, oil, gas) to CO2 emissions.

## Installation

To run this project locally, you need to have Python installed along with the necessary libraries. You can install the required packages using the following command:

```bash
  pip install pandas numpy panel hvplot
```

## Usage

**1.** Clone the repository or download the Jupyter notebook.
**2.** Open the notebook in Jupyter or JupyterLab.
**3.** Run the notebook cells sequentially to generate the dashboard.
**4.** Interact with the dashboard using the widgets provided to explore the CO2 emission data.

## Conclusion

This project demonstrates the power of Panel in building interactive dashboards directly within a Jupyter Notebook. The CO2 Emission Dashboard serves as a valuable tool for visualizing and understanding the impact of CO2 emissions across different regions and over time.
