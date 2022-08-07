# Greater-Manchester-Area-Airbnb-Analysis
1. [ Introduction ](#intro)
2. [ Installations ](#installations)
3. [ Project Motivation ](#projectMo)
4. [ File Description ](#file)
5. [ Summary of Results](#SummaryofResults)
6. [ Licesnsing and Acknowledgement ](#licensing)

<a name="intro"></a>
## 1. Introduction

This is an analysis of Airbnb listings in the Greater Manchester Area as at March, 2022. The dataset used has 3584 listings with information like price, host information, amenities, ratings and many other features present in the dataset. 

<a name="installations"></a>
## 2. Installations

- Python
- Numpy
- Pandas
- Seaborn
- Matplotlib
- Scikit Learn

<a name="projectMo"></a>
## 3. Project Motivation

The following questions served as a guide in the analysis of listings in the Greater Manchester Area. 
- What areas or towns have the most airbnb listings?
- What are the best type of listings based on ratings data?
- What are the price characteristics of Airbnb listings in the Greater Manchester Area?
- What is the spread of listings per host?
- What type of rooms are available in the Greater Manchester Area?
- Can a machine learning model be used to predict prices of Airbnb listings in the area?

<a name="file"></a>
## 4. File Description

* Data: contains the datasets used in the analysis. 
* airbnb_updated: A copy of the notebook used for the analysis. 

<a name="SummaryofResults"></a>
## 5. Summary of Results

1. Manchester town has the most listings in the Greater Manchester Area, accounting for 53% of total listings followed by Salford with 17% and Trafford with about 9% of total listings.

2. Amongst the top 10 most reviewed property types by customers, "Entire Cottage" had the highest median rating of 4.9 followed by entire bungalow, tiny home, private room in a residential home and private room in a townhouse.


3. 65.4% of total listings were priced between $0–$100 while $100–$200 priced listings accounted for 23.4% of total listings.
The bulk of the property listings were entire homes/apartments. The 'entire rooms' accounted for about 60% of total listings followed by private rooms with 39% of listings.Shared rooms and hotel rooms accounted for 0.7% and 0.5% of listings respectively.


4. The RandomForestRegression algorithm performed best in predicting prices of listings in the Greater Manchester Area. The model achieved a root mean square error of 32 and an R² value of 59.8% which means that the features are able to explain 60% of the variability in the price of the listings. 

Here's a link to my medium article detailing the major findings: [Medium Article](https://medium.com/p/72156f8f5554/edit)


<a name="licensing"></a>
## 6. Licesnsing and Acknowledgement

The datasets used in this analysis were acquired from Inside Airbnb database under a 
Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication" license.



