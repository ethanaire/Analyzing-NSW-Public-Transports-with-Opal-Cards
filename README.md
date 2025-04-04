# Analyzing NSW Public Transports - Opal Cards' Tap-ons and Tap-offs 

This repo is a re-up/reorganization/refinement of the same project finished in 2022.

## Project Goals: 
- Analyse different sections of the transport usage in NSW by evaluating the relationship between the tap-on and tap-off rates of Opal cards in 4 suburbs (Parramatta, Strathfield, Chatswood, and Macquarie Park). 
- Compare the total uses of different transport modes in NSW, for example, monthly usage of trains and buses over a long period, and examine the impact of demographic factors (age group or weekly personal income) on traveling trends.
- Cluster the dataset into high and low transport uses groups. Therefore we could determine which period of months the uses of transport were affected significantly (i.e. had the lowest records of uses), and we find out the Covid-19 lockdown could be considered as one of the factor affect on the transport usage.

## Data Sources: 
The datasets used in the project are data scraped from Transport NSW and the Australian Bureau of Statistics.
<br><ul>
<li> Transport NSW: Data recorded hourly for each type of transport, can be used for analyzing the number of tap-ons and tap-offs each day during a week for each suburb. 
<li> Census Table Builder (2016 - from Australian Bureau of Statistics) reports individual weekly income. The data is divided in brackets, ranging from negative and nil income, then the lowest range of $1 to $149 per week to the highest range of over $3000 per week. The salary data is recorded in the following format: weekly (annually). </ul>
<br> Combining the two datasets, we can analyze and predict the relationship between transport and income.

## Methodologies:
<ol>
<li> Data Cleaning <br>
<ul><li> <u> Format: </u> Rearrange the data format to be readable in the notebook environment.
<li> <u> Data Cleaning: </u> Replace NaN values in the <i>Metro</i> column in the <i>Transport NSW</i> dataset to 0 as there is no metro service until mid-2019. </ul></br>
<li> Techniques </br>
<ul>
  <li> Linear Regression for continuous variable prediction (e.g. number of tap-on events).
  <li> Logistic Regression, K-nearest Neighbour, Gaussian Naive Bayes and Multi-Layer Perception (MLP) Classifier & Neural Networks for discrete variable prediction (e.g. age group/ income group).
  <li> Hierarchical Clustering for finding hidden structure where the records have similar feature within a group (e.g. cluster into high uses of transport group)
</ul><br>
<li> Languages: Python </li><br>
<li> Libraries
<ul>
  <li> Pandas
  <li> Numpy
  <li> Seaborn
  <li> SKlearn 
</ul></ol>


