# Suicide Rates Overview - 1985 to 2016
The statistical analysis of suicides in countries from 1985 to 2016


## Introduction
To analyse the suicides rates overview from 1985 to 2016 using the dataset found in kaggle by finding
meaningful insights using inferential statistics along with descriptive statistics. Our main objective is to
determine whether the gdp of the country is a strong factor in determining the suicide rates of that country,
whether any particular gender is more prone to committing suicide also to determine the pattern of suicide
rates across all countries over the years.

The raw data is obtained from Kaggle(https://www.kaggle.com/). The data is titled “Suicide Rates
Overview 1985 to 2016” which compares socio-economic info with suicide rates by year and country. The
data is collected from 30 countries from 1985 to 2016 in which there are 8 columns which can be analyzed to
find information and correlation to suicide rates among different cohorts globally, across the socio-economic
spectrum.

## Analysis

The project focuses onn statistical analysis on the data and publishes the interesting findings. The report contains detailed information about the analysis. However, the following topics show the kind of analysis done on the data:

* Correlation - GDP per Capita vs Number of Suicides
* Hypothesis to test the sample countries have number of suicides less than the
  mean number of suicides
* Hypothesis to test the difference in mean number of suicides between Generation
  X & Boomers
* Joint Probability for top 20 Countries over the years
* Suicide rate for Male & Female over the years
* The Confidence Interval for the mean number of suicides committed by male in
  1988 with 95% confidence
  
## Approach

The dataset has been analysed using R programming language. It makes use of data wrangling packages available in R such as dplyr, tidyr and fitdistrplus package for fitting the distribution on the dataset. The outputs have been visualized using the ggplot2 and Tableau. Necessary care has been taken in analysis to avoid incorrect information. For example, considering suicides per 100k capita instead of number of suicides such as to bring the rate to similar scale.
