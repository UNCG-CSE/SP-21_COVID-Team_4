## **Covid Data Analysis** - Group Project (CSC-405-605_Spring_2021)


#### An analytical system to understand and visualize the patterns of COVID-19 effect and spread across different counties of the United States.

### Table of Contents

***

+ #### [Project Description](#Project-description)
+ #### [Stage I - Data and Project Understanding](#Stage-i-data-and-project-understanding)
  * ##### [COVID-19 Dataset](#Covid-19-dataset)
+ #### [Stage II - Data Modeling and Hypothesis Testing](#Stage-2)
+ #### [Stage III - Basic Machine Learning](#Stage-3)
+ #### [Stage IV - Dashboard](#Stage-4)
+ #### [Technologies Used](#Tech-used)
+ #### [Project Status](#Status)
+ #### [Sources](#source)



<a name="Project-description"></a>
### Project Description

***

This project aims to examine COVID-19 data from the United States in order to view possible trends in the virus’s spread. This involves analyzing the number of cases, the number of deaths, and the various counties’ populations. Along with this, many other aspects by county are considered, including hospital beds, presidential election results, employment, economic characteristics, and demographic information.

With this data, we plan to develop linear and non-linear regression models for predicting the number of cases of and the deaths due to COVID-10 in the United States. We aim to process the data using statistical models and present it in a meaningful way using graphs with a trendline, confidence intervals, and a prediction path. After plotting daily trends, we intend to show our results on a main graph that shows past trends and the forecast of future trends. We will plot cases and deaths on a map of the United States using mean county population to normalize for cases and deaths.

<a name="Stage-i-data-and-project-understanding"></a>
### Stage I - Data and Project Understanding

***

This is the first stage of the project where we get acquainted with the **COVID-19 dataset**. These datasets are provided by [USAFacts](https://usafacts.org/). We have utilized the daily county-level tracker of COVID-19 cases in the US. You can use the links below to download the granular level data from USAFacts.

<a name="Covid-19-dataset"></a>
#### COVID-19 Dataset

  + [Stats by Number of Cases](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv)
  + [Stats by Number of Deaths](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv)
  + [Stats by Population](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv)

<a name="Stage-2"></a>
### Stage II - Data Modeling and Hypothesis Testing

***


This is the second stage of the project where dig into data modeling and hypothesis testing. With the preliminary intuitions we had in stage 1, we are going to develop a formal hypothesis and use statistical modeling to prove or disprove. We are going to compare the weekly statistics by using mean, median, mode for our 3 main variables and plot the daily trends in a meaningful way. We will try to search correlation between different data sets. Also, we will be comparing the data of the United States against other countries in the world with the **World dataset**.

#### COVID-19 Worldwide Dataset.

  + [Worldwide Dataset](https://ourworldindata.org/coronavirus-source-data)

<a name="Stage-3"></a>
### Stage III - Basic Machine Learning

***


In this stage, we dive into developing linear and non-linear regression models for predicting the cases and deaths in the United States. Machine learning and statistical models will be used to predict the trend of COVID-19 cases/deaths. We will plot trend line and forecast our prediction of 1 week ahead. Confidence intervals will be introduced to analyze the error in prediction. This is also the stage of the project where we perform hypothesis tests on the questions we identified in stage 2 of the project.

<a name="Stage-4"></a>
### Stage IV - Dashboard

***


With the use of frameworks like Plotly along with Dash, we intend to develop a simple interactive dashboard for our fourth and final stage of the project. We will allow for the selection of dates, states and linear or log mode to discover the data we have and have a main graph that displays these queries. Finally, we will do a presentation to present our overall project and showcase our hard-work.


<a name="Tech-used"></a>
### Technologies Used

***

+ Python - Version 3.7
+ Jupyter Notebook
+ Pandas

<a name="Status"></a>
### Project Status

***

Stage I: Complete

Stage II: Incomplete

Stage III: Incomplete

Stage IV: Incomplete



<a name="source"></a>
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
