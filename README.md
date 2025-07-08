# World Economic Report

## The Situation
You've just been hired as a Data Journalist for The Numbers, a magazinr that focuses on global economic news and issues.

## The Assignment
The World Bank has just released its annual economic report, which includes data on every country's economy and development statistics.
You've been asked to produce an infographic-style report highlighting major trends in global economic growth and development.

## The Objectives
1. QA and Profile the World Bank data, and join additional UN Data to it.
2. Prepare and reformat the data for visualization.
3. Create visualizations that depict key trends and relationships in the data.
4. Combine your visualizations into a single report style graphic.

## The Data Set

#### World Economic Indicators
The World Bank funds infrastructure projects in the developing world. As part of its mission, it releases an annual report on economic indicators. This dataset includes important indicators of economic performance and development from 1960-2018, including fields like electricity consumption, GDP per capita, life expectancy, and more.

To augment the World Bank data, Human Development Index (HDI) data has been provided by the United Nations (UN). HDI is a composite measure of how developed a country is based on life expectancy, GDP per capita, and educational attainment. This supplementary dataset contains additional indicators used by the UN to track development, environmental impact, and inequality for each country from 1990-2021. 

#### Recommended Analysis
1. Which countries have experienced the highest growth in population and GDP? Is there overlap?
2. Which regions saw the most growth in HDI in the 21st century?
3. Which factors are highly correlated with life expectancy?
4. Which factors differentiate "High Income" vs "Low Income" Countries?

#### Objective 1: Prepare & QA the data
Your first objective is to get the data ready for analysis by importing and joining the data, creating new columns, and performing basic profiling and QA.

* Import the WorldBank.xlsx file.
* Use "GDP" and "GDP per Capita" to calculate population in millions and create a "Population (M)" column.
* Perform basic profiling & QA on the data.
* Filter the data to 2014 and join it with the hdi.csv file on "Country Code".

#### Objective 2: Prepare the data for visualization
Your second objective is to transform and shape the data into tables that will be used as the source for data visualizations.

* Create a "gdp_pivot" table with years as rows, regions as columns, sum of GDP as values.
* Create "pop_pivot" table with years as rows, regions as columns, and sum of population as values.
* Create "wb_hdi_by_region" table by calculating the average HDI for each region and sorting from highest average HDI to lowest.

#### Objective 3: Visualize the data
Your third objective is to create 5 charts to visualize trends, relationships, and comparisons across regions.

* Create a stacked area chart showing the growth of GDP over time, with each stack representing a geographic region.
* Create a stacked area chart showing the growth of population over time, with each stack representing a geographic region.
* Create a bubble chart with life expectancy for each country in the x-axis, GDP per capita in the y-axis (log scale), and population as the bubble size. Color the bubbles by region using the same colors for each as in the previous charts.
* Create a bar chart to show average HDI by region (make sure the region colors match).
* Create a scatterplot with power consumption in the x-axis and GDP per capita in the y-axis, then use HDI as a color scale for the dots (make sure to remove outliers like Iceland).

#### Objective 4: Build a final report
Your final objective is to structure your visualizations into a compelling report on the state of the global economy.

* Assemble the 5 visualizations you have created into a single page (or figure).
* Add an overall title and descriptive text to add context for the reader.

#### [Project Link]()