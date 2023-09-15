 ---
title: "AI driven tunnel drilling"
date: 2018-06-08T15:06:32+02:00
draft: true
author: "Stephan Munsch"
tags: [Artificial Intelligence, Predictive Maintenance, Data Exploration, Data Science]
summary: "Unearthing Efficiency: Revolutionizing Tunnel Drilling Through Predictive Maintenance"  
---

I am a software engineer at [QAware](https://www.qaware.de) in Munich. 


## Maidl TC
describe [Maidl TC](https://www.maidl-tc.de/en/index.html) and what are they doing.
Software PROCON is used to monitor tunnel boring machines in realtime???

## The vision
Utilize the collected data to train a ai model which helps tunnel boring companies with their project due to minimizing maintenance windows with predictive maintenacne.

## Business Understanding
Each tunnel borer is unique and is planned and produced individually for each tunnel. 
In addition, the tunnel drills are very expensive to manufacture and operate. The value of the specific energy plays a major role here. 
The specific energy describes the total energy that the tunnel borer has to expend in order to advance. 
Thus, the specific energy is a good cost indicator for the drilling project. 
On the other hand, there are the cost drivers: tool wear and the amount of drilling foam used.
The amount of drilling foam used has a direct impact on tool wear. 
If too little foam is used, the tools will wear faster,
if too much foam is used, this can lead to poor drilling performance.

`TODO: description how we made the decision for anomalie detection with LSTMs == Task`

## Data Understanding
we got a good amount of already preprocessed data from maidl with various parameters from a previous project
Needed understand: 
* what kind of data do we have here (value wise) 
* are these already preprocessed
* can we perform the given Task with the given data
* which data are related to eachother 
* which data are usefull for the Task

## Data Preparation
Filtering the data and reducing the parameters to a certain amount which can be used to train a ai model

## Modeling
* Neural Network for predicting certain parameters
* LSTM for predicting future values
* LSTM for anomaly detection


## Evaluation
* evaluation with SHAP Values and explainable AI -> did we choose the right parameters for our results
* 

## Lesson's learned
we learned a lot!
