## **Covid Data Analysis** - Group Project (CSC-405-605_Spring_2021)
<hr>

##### An analytical system to understand and visualize the patterns of COVID-19 effect and spread across different counties of the United States

### Table of Contents
* #### [Project Description](#project-description)
* #### [Stage I - Data and Project Understanding](#stage-i-data-and-project-understanding)
  * ###### [COVID-19 Dataset](#covid-19-dataset)
* #### [Stage II - Data Modeling and Hypothesis Testing](#stage-2)
* #### [Stage III - Basic Machine Learning](#stage-3)
* #### [Stage IV - Dashboard](#stage-4)


### Project Description

This project aims to examine COVID-19 data from the United States in order to view possible trends in the virus’s spread. This involves analyzing the number of cases, the number of deaths, and the various counties’ populations. Along with this, many other aspects by county are considered, including hospital beds, presidential election results, employment, economic characteristics, and demographic information.

With this data, we plan to develop linear and non-linear regression models for predicting the number of cases of and the deaths due to COVID-10 in the United States. We aim to process the data using statistical models and present it in a meaningful way using graphs with a trendline, confidence intervals, and a prediction path. After plotting daily trends, we intend to show our results on a main graph that shows past trends and the forecast of future trends. We will plot cases and deaths on a map of the United States using mean county population to normalize for cases and deaths.

### Stage I - Data and Project Understanding

This is the first stage of the project where we get acquainted with the **COVID-19 dataset**. These datasets are provided by [USAFacts](#https://usafacts.org/). We have utilized the daily county-level tracker of COVID-19 cases in the US. You can use the links below to download the granular level data from USAFacts.

#### COVID-19 Dataset

  + [Stats by Number of Cases](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv)
  + [Stats by Number of Deaths](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv)
  + [Stats by Population](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv)
