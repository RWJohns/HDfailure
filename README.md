# Hard drive failure prediction model

## Project Overview:
BlackBlaze has posted data on Harddrive failure. Understanding these failures is import for 2 major reasons. first, data centers are becoming an increasingly imporant part of our economy as we move into more data centric buisness models. second, as we allow computers to increasingly control the world around us it's important that we can predict critical device failures before they occur in order to increase safety and user experience. 


## Data Sources:
Kaggle Blackblaze Data (Dataset Link)[https://www.kaggle.com/awant08/hard-drive-failure-prediction-st4000dm000/version/1]


## Methodology:
* EDA of dataset and identify features that strongly correlate with failur
* Use AWS computer to manipulate data in a SQL database
* Apply classification models (Knn, logit, etc.) to build a strong prediction model 
* train model on a single year's data and try to predict performance in other years (there are 4 years worth of data)
* train a model on data from all 4 years mixed togeter using a train-validate-test methodology to arrive on the strongest model.

## MVP:
MVP: Make a Classification model that can predict that a HD is going to fail

## Target
Device failure 

## Features:
date
serial_number
model
capacity_bytes
- S.M.A.R.T. device error code occurences (data set has 45 features, I likely will not use all of them)
(S.M.A.R.T. Code guides)   [https://en.wikipedia.org/wiki/S.M.A.R.T.]

### Potential additional step:
* integrate information based on the product number to other characterisitics of drives since they vary in storage space
