---
layout: post
## CSE 4334

# DATA MINING

# KAGGLE MACHINE LEARNING

# COMPETITION(TITANIC)

## Introduction

The RMS Titanic sank in the early morning hours of 15 April 1912 in the North Atlantic
Ocean, four days into her maiden voyage from Southampton to New York City. Kaggle, an
online community of data scientists and machine learning practitioners created a beginner
friendly ML competition inspired by the tragic story of the Titanic. The goal of the
competition is to create a model capable of accurately predicting whether a passenger had
survived the accident or not.


### Data

In order to train and develop a somewhat accurate model, Kaggle provided three sets of
data. The first onetrain.csvcontains the detailsof a subset of the passengers on board
(891 passengers, to be exact -- where each passenger gets a different row in the table). This
data set indicates if each passenger survived or not.

The second onetest.csvdataset contains similar informationbut does not disclose the
faith for each passenger.


Lastly, thegender_submission.csvfile is provided as an example that shows how you
should structure your predictions. It predicts that all female passengers survived, and all
male passengers died.

### Methodology

The methodology suggested to approach this beginner ML competition was to use the
training dataset (train.csv) to find variables and patterns to implement on the test dataset
(test.csv). Inspiring ourselves from how thegender_submission.csvfile produced a
somewhat accurate result leveraging only a single attribute. We built a random forest
model based on the four following attributes: socio economic status, siblings/spouse on
board, parent/children on board and finally gender.

#### Implementation

1- Random forest model


2- Code

#### Results

Model predictions


