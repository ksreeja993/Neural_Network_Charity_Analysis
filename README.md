# Neural_Network_Charity_Analysis.
## Overview of the analysis:
create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Deliverables:

* Deliverable 1: Preprocessing Data for a Neural Network Model
* Deliverable 2: Compile, Train, and Evaluate the Model
* Deliverable 3: Optimize the Model
* Deliverable 4: A Written Report on the Neural Network Model (README.md)

## Data:
A charity data csv containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively
![2](https://user-images.githubusercontent.com/105166481/197109073-5b93b23b-6a14-4e37-94dd-103415509863.png)
![Screenshot 2022-10-20 130359](https://user-images.githubusercontent.com/105166481/197109075-32de6265-2cf7-45e8-b210-1e51120b2e4a.png)

## Data Preprocessing:

The variables that are not adding value to the model are dropped and name and application type variables are binned and bucketed to make the model more efficient.

## Results:

The final model accuracy is 0.81 as shown in the figure below.

![4](https://user-images.githubusercontent.com/105166481/197109044-581914c8-d8e8-46df-8689-028bab3b9a18.png)



