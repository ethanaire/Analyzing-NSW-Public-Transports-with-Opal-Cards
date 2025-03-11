COMP2200-S2-2021

Group members: <br>
Dong Ha Nguyen Luu <br>
Xuyen Linh Huynh <br>
Xuan Dung Vuong <br>
Hai Hoang Nguyen

This repository contains the notebook for our project and files for original dataset by excel. 

Datasets: Our datasets were collected from the Transport of NSW and the Australian Bureas of Statistic (Census 2016). In this project, we mostly work on the data of transport uses, and find out the relationship between age/income group and the transport usage.

Goals:
- To predict the tap-on events at the stops of one suburb based on the tap-off at the stops of another nearby suburb, hence giving information for passenger to plan ahead during the Covid-19 restriction.
- To predict the age group and income group based on the uses of various transport services. Thus, we could study whether there is a relationship between some demography and the uses of transport services.
- To cluster the dataset into high and low transport uses groups. Therefore we could determine which period of months the uses of transport were affected significantly (i.e. had the lowest records of uses), and we find out the Covid-19 lockdown could be considered as one of the factor affect on the transport usage.

Techniques:
- Linear Regression for continuous variable prediction (e.g. number of tap-on events).
- Logistic Regression, K-nearest Neighbour, Gaussian Naive Bayes and Neural Network for discrete variable prediction (e.g. age group/ income group).
- Hierarchical Clustering for finding hidden structure where the records have similar feature within a group (e.g. cluster into high uses of transport group)
- Bar chart, line graph, regression plot, scatter plot, etc. for visualisation.

Datasets:  

- Dataset 1: Using the linear regression to predict the tap-on based on tap-off data within 4 suburbs: Macquarie Park, Chatswood, Strathfield and Parramatta. 

- Dataset 2: Using Logistic Regression, K-nearest Classifier, Guassian Naive Bayes and Multi-layer Perception to analyse the effect of personal weekly income to the usage of public transport. 

- Dataset 3: Using the same techniques as Dataset 2 in order to predict the usage of public transport based on age group.

- Dataset 4: Identifying and Clustering the uses of transport modes. Identify which transport is more popular compared to other transports. 
