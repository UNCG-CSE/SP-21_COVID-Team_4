## **Covid Data Analysis** - Group Project (CSC-405-605_Spring_2021)
<hr>

#### An analytical system to understand and visualize the patterns of COVID-19 effect and spread across different counties of the United States.

### Table of Contents

***

* #### [Project Description](#project-description)
* #### [Stage I - Data and Project Understanding](#stage-i-data-and-project-understanding)
  * ###### [COVID-19 Dataset](#covid-19-dataset)
* #### [Stage II - Data Modeling and Hypothesis Testing](#stage-2)
* #### [Stage III - Basic Machine Learning](#stage-3)
* #### [Stage IV - Dashboard](#stage-4)
* #### [Technologies Used](#tech-used)
* #### [Project Status](#status)
* #### [Sources](#sources)


<a name="project-description"></a>
### Project Description

***

This project aims to examine COVID-19 data from the United States in order to view possible trends in the virus’s spread. This involves analyzing the number of cases, the number of deaths, and the various counties’ populations. Along with this, many other aspects by county are considered, including hospital beds, presidential election results, employment, economic characteristics, and demographic information.

With this data, we plan to develop linear and non-linear regression models for predicting the number of cases of and the deaths due to COVID-10 in the United States. We aim to process the data using statistical models and present it in a meaningful way using graphs with a trendline, confidence intervals, and a prediction path. After plotting daily trends, we intend to show our results on a main graph that shows past trends and the forecast of future trends. We will plot cases and deaths on a map of the United States using mean county population to normalize for cases and deaths.

<a name="stage-i-data-and-project-understanding"></a>
### Stage I - Data and Project Understanding

***

This is the first stage of the project where we get acquainted with the **COVID-19 dataset**. These datasets are provided by [USAFacts](#https://usafacts.org/). We have utilized the daily county-level tracker of COVID-19 cases in the US. You can use the links below to download the granular level data from USAFacts.

<a name="covid-19-dataset"></a>
#### COVID-19 Dataset

  + [Stats by Number of Cases](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv)
  + [Stats by Number of Deaths](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv)
  + [Stats by Population](#https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv)
  
<a name="stage-2"></a>
### Stage II - Data Modeling and Hypothesis Testing

***

<a name="stage-3"></a>
### Stage III - Basic Machine Learning

***

<a name="stage-4"></a>
### Stage IV - Dashboard

***


<a name="tech-used"></a>
### Technologies Used

***

+ Python - Version 3.7
+ Jupyter Notebook
+ Pandas

<a name="status"></a>
### Project Status

***

Stage I: Complete

Stage II: Incomplete

Stage III: Incomplete

Stage IV: Incomplete

<a name="sources"></a>
### Sources

***

+ [Visualization](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)
+ [Confirmed COVID-19 Cases](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv)
+ [COVID-19 Deaths](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv)
+ [County Populations](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv)
+ [Census Demographic ACS](https://data.census.gov/cedsci/table?q=dp&tid=ACSDP1Y2018.DP05)
+ [Economic ACS](https://data.census.gov/cedsci/table?q=dp&tid=ACSDP1Y2018.DP05)
+ [Employment](https://www.bls.gov/cew/downloadable-data-files.htm)
+ [Presidential Election Results](https://www.kaggle.com/unanimad/us-election-2020)
+ [Hospital Beds](https://coronavirus-resources.esri.com/datasets/1044bb19da8d4dbfb6a96eb1b4ebf629_0/data?geometry=-40.957%2C-16.820%2C15.996%2C72.123)

