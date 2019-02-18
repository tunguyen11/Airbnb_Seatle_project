# Airbnb Seatle Project
In this project, I will follow the CRISP-DM method for, preparing, analyzing, model and visualizing data and answering three business-related questions related to Airbnb data on Seattle 

## Business questions:

#### 1. How well can a machine learning model predict the rental price listing? 
#### 2.  What are the key features that determine the price? 
#### 3. How the price and availability of the rental vary across months? 

## Installations
* The project is done in Jupyter Notebook (Anaconda). Python 3.6.
* sklearn
* numpy
* pandas 
* seaborn
* matplotlib

## Files
* listings.csv:
* calendar.csv

These data can be downloaded from http://insideairbnb.com/get-the-data.html
* Jupyter Notebook: The project contains a Jupyter notebook where all the technical sides of the project have been conducted,


## Findings 

#### 1.  After trying different models and tunning hyperparameters, I found that the best model to predict rental listing price is RandomForestRegressor. The best R2 score is 0.573 
#### 2. I found the five most important features are: number of bedrooms, number of bathrooms, cleaning fee, average number of review per month, Private Room or not
#### 3. I found that the rental price listing is highest in June, July, and August. In these months, the availability of rental listing is also lowest. This is possibly due to the high demand of room during the traveling season in Seattle during summer 


## Licensing, Authors, Acknowledgements, Authenticity. 
I confirm that this project is done solely by myself.
