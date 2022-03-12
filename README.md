## Covid Data Analysis - Group Project (CSC-405-605_Spring_2021)


#### An analytical system to understand and visualize the patterns of COVID-19 effect and spread across different counties of the United States

### Table of Contents

***

+ #### [Project Description](#project_descriptions)
+ #### [Data and Project Understanding](#data_and_project_understanding)
  * ##### [COVID-19 Dataset](#covid_19_dataset)
+ #### [Data Modeling and Hypothesis Testing](#data_modeling_and_hypothesis_testing)
  * ##### [COVID-19 Worldwide Dataset](#covid_worldwide_dataset)
+ #### [Stage III - Basic Machine Learning](#basic_machine_learning)
+ #### [Stage IV - Dashboard](#dashboard)
+ #### [Technologies](#technologies)
+ #### [Project Setup](#project_setup)
+ #### [Project Status](#project_status)
+ #### [Sources](#source)



<a name="project_descriptions"></a>
### Project Description

***

This project aims to examine COVID-19 data in the United States in order to view possible trends in the virus’s spread. This involves analyzing the number of cases, the number of deaths, and the various counties’ population. This data is combined with several enrichment dataset like hospital beds, presidential election results, employment, economic characteristics, and demographic information.

Covid-19 dataset combined with the enrichment dataset can help understand the pattern in the change in number of cases and deaths and their correlation with different factors. Using these data, a linear and non-linear regression models is developed for predicting the number of cases and deaths due to COVID-10 in the United States. The data is processed using statistical models and presented using graphs with a trendline, confidence intervals, and a prediction path. Ultimately, a simple interactive dashboard is created based on the analysis where user can visualize the present trend, predictions, moving average and more.

<a name="data_and_project_understanding"></a>
### Stage I - Data and Project Understanding

***

This is the first stage of the project where we get acquainted with the **COVID-19 dataset**. These datasets are provided by [USAFacts](https://usafacts.org/). We have utilized the daily county-level tracker of COVID-19 cases in the US. You can use the links below to download the granular level data from USAFacts.

<a name="covid_19_dataset"></a>
##### COVID-19 Dataset

  + [Stats by Number of Cases](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv)
  + [Stats by Number of Deaths](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_deaths_usafacts.csv)
  + [Stats by Population](https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_county_population_usafacts.csv)


<a name="data_modeling_and_hypothesis_testing"></a>
### Stage II - Data Modeling and Hypothesis Testing

***


This is the second stage of the project where we dig deep into data modeling and hypothesis testing. With the preliminary intuitions we had in stage 1, we develop a formal hypothesis and use statistical modeling to prove or disprove the hypothesis. We compare the weekly statistics by using mean, median, mode for our 3 main variables and plot the daily trends in a meaningful way. We also search for correlation between different features. Additionally, we compare the data of the United States against other countries with the **World dataset**.

<a name="covid_worldwide_dataset"></a>
##### COVID-19 Worldwide Dataset.

  + [Worldwide Dataset](https://ourworldindata.org/coronavirus-source-data)

<a name="basic_machine_learning"></a>
### Stage III - Basic Machine Learning

***


In this stage, we dive into developing linear and non-linear regression models for predicting the cases and deaths in the United States. Machine learning and statistical models are used to predict the trend of COVID-19 cases/deaths. We also plot trend line and forecast our prediction of 1 week ahead. Confidence intervals is introduced to analyze the error in prediction. Hypothesis testing on the hypothesis formulated in stage 2 of the project is performed.

<a name="dashboard"></a>
### Stage IV - Dashboard

***


With the use of frameworks like Plotly along with Dash, we develop an interactive dashboard for our fourth and final stage of the project. We allow for the selection of date(s), states and linear/log normalization as different methods to filter the data and present the result/ analysis in a group. This group is interactive and also easily interpretable.

[This](https://www.github.com/UNCG-CSE/SP-21_COVID-Team_4/blob/main/doc/Pratik_CSC405_605%20-%20Report_Stage_IV.pdf) document details further about the dashboard, provides different snapshots along with a short description of what each snapshot represents.


<a name="technologies"></a>
### Technologies:

***

+ Python: 3.7
+ Jupyter Notebook: 6.2.0

<a name="project_setup"></a>
### Project Setup:
***
To run this project locally, make sure you have [python](https://wiki.python.org/moin/BeginnersGuide/Download), [pip](https://pip.pypa.io/en/stable/installing/) and [jupyter notebook](https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html) installed. You will also need some additional python libraries to run the project properly. You can install all libraries using the code below. On your project parent directory, run:

```
pip install -r requirements.txt
```

To open jupyter notebook, while you are in the project's parent directory, run:
```
jupyter notebook
```


<a name="project_status"></a>
### Project Status

***

Stage I: **Complete**

Stage II: **Complete**

Stage III: **Complete**

Stage IV: **Complete**



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
