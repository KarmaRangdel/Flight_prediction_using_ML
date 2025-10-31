# Flight_prediction_using_ML
This repository contains the flights delays prediction using machine learning classification model. 
Detailed data pre-processing and EDA is done.
Logistic regression model is applied
Model is evaluated using multiple evaluation metrics.
## The ML problem statement
Given a set of features, can you predict if a flight is going to be delayed more than 15 minutes?
Because the target variable takes only 0/1 value, you could use a classification algorithm.
## Dataset Details:
The provided dataset contains scheduled and actual departure and arrival times reported by certified US air carriers that account for at least 1 percent of domestic scheduled passenger revenues. The data was collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS). The dataset contains date, time, origin, destination, airline, distance, and delay status of flights for flights between 2014 and 2018. The data are in 60 compressed files, where each file contains a CSV for the flight details in a month for the five years (from 2014 - 2018). The data can be downloaded from this link. Please download the data files and place them on a relative path. Dataset(s) used in this assignment were compiled by the Office of Airline Information, Bureau of Transportation Statistics (BTS), Airline On-Time Performance Data, available with the following link (https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ).
## Machine learning pipeline:
#### 1: Data loading and pre-processing
#### 2: EDA and Visualization
#### 3: Modeling  (Logistic Regression) and performance evaluation using accuracy, recall, precision and f1-score.
## How to run code?
#### Editor: Google Colab
First of all download dataset from above link.  Then download this onpremisis_code.ipynb file and upload it on Google Colab from File option. Also upload data.zip file and then install necessary libraries.
Now you can run code easily.
This code is baseline for flight delays prediction. Though model performed well but in future data balancing and fine tuning is required.
Thank you!


