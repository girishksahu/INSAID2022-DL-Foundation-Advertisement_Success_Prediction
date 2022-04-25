# INSAID2022-DL-Foundation-Advertisement_Success_Prediction
INSAID 2022 Deep Learning Foundation Term Project

# Project Description
## Introduction
- Your client for this project is an Advertisement Production Company.

    - They want to produce good quality, precise advertisements to increase more engagement when the item/product is sold.

    - They have experience in producing high-quality ads for various ranges of products being sold in different parts of the world.

    - To find useful insights for better ad production, they need to analyze different parameters of their previous ads.

## Current Scenario
- They have a collection of different instances of advertisements of different products aired in different countries.

- They don’t have any means to predict the success of a future advertisement and there is a requirement to automate this process.

- However, Designing a computer program to do this turns out to be a bit trickier.

- Currently, the organization is keeping track by manually assigning surge prices to its customers.

## Problem Statement
The current process suffers from the following problems:

- There are various factors responsible for deciding whether an advertisement will gain profit or not.

    - Analyzing those factors and drawing useful insights from it to produce more precise advertisements accordingly requires too many considerations.

    - This becomes quite a challenging and time-consuming task

- The company has hired you as a data science consultant.

    - They want to automate the process of predicting whether an advertisement will incur a gain when sold or not.

## Project Task
* Dataset contains all the necessary information about various advertisements.
* Project task is to build a classification model for predicting netgain.
## Project Deliverables
- Deliverable: **Predict whether an advertisement will be profitable or not.**
- Machine Learning Task: **Classification**
- Target Variable: **netgain**
## Evaluation Metric
* The model evaluation will be based on the Accuracy score.
# Data Description
* The columns contains all the necessary information which might affect the netgain.
* The column netgain is also present in the dataset which is a measure of the overall gain from ad.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 20838 rows and 12 columns.
* The column netgain is the target variable.

## Test Set:
* The test set contains 5210 rows and 11 columns.
* The test set doesn’t contain the netgain column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique ID                     |
|02| **Relationship_status** | If the person is married, divorced or never married              |
|03| **Industry**   | Type of industry                  |
|04| **Genre** | Type of genre         |
|05| **Targeted_sex**   | Targeted sex of the audience             |
|06| **average_runtime(minutes_per_week)** | Runtime per week              |
|07| **airtime**   | airtime of the advertisement                   |
|08| **airlocation** | Location of the advertisement aired             |
|09| **Ratings**   | Ratings of the adverstisement                   |
|10| **Expensive** | If it is expensive or not             |
|11| **money_back_guarantee**   | If there is money back gurantee or not                 |
|12| **Netgain** | If there will be profit or not            |
