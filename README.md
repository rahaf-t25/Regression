# Regression

## Airbnb price prediction

This dataset of Airbnb that allows people to rent and rent accommodation in different cities. The host creates his own profile page, and a profile page for his rental property that also contains recommendations from other people, reviews from the property's guests, and an evaluation of the property.


## Contents

-[Problem Statement](#Problem_Statement)

-[Data Description](#Data_Description) 

-[Tools](#Tools)

-[Models](#Models)

-[Installation](#Installation)

-[Questions](#Questions)

-[MVP](#MVP)

-[Dataset Resource](#Dataset_Resource)

-[Author](#Author) 

![Logo](https://a0.muscache.com/im/pictures/5abcc13e-d206-414c-9c8b-e84d1b649aeb.jpg?aki_policy=large)


## Problem_Statement

The scope of this dataset is the United States of America. The aim of the study is to increase the number of Airbnb hosts by analyzing the dataset and learn about the properties of the real estates offer to support real estetes that meet the company's standards.
### Data_Description

Dataset: Airbnb prices

It has 74,111 rows , 29 columns.

| Field Name        | Description| Type|  
| ------------- |:-------------:|:------------:|
| ID| Unique identifier for each property|int64 | 
| log_price| property price| float64|
| property_type| Apartment, House, Condominium, Loft, Townhouse, Hostel etc.|Object |
|room_type| Is it the whole house/apartment, private room or shared room etc.|Object|
| amenities| any feature that provides comfort, convenience, or pleasure |Object |
| accommodates| How much does the property accommodate a person? |int64  |
| bathrooms| Number of bathrooms |float64 |
| bed_type|  Is it a Real Bed, Airbed or Pull-out Sofa etc. |Object |
| cancellation_policy| Is the cancellation policy complicated or flexible? | Object|
| cleaning_fee|  Is there a fee for the cleaning service?  | bool    |
| city|  Where is the property located?  | Object|
| description|  Long description of the property  | object |
| first_review|  The date of the first property review   | Object|
| host_has_profile_pic|  Is there a profile picture for the host account?  | object  |
| host_identity_verified|  Host ID Authentication  | Object|
| host_response_rate|  Is the host responsive to his customers or not?  | Object |
|host_since|Start date of being a host|object |
|instant_bookable|Can the customer book immediately?|object |
|last_review|The date of the last property review|object |
|latitude|Coordinates|float64|
|longitude|Coordinates|float64|
|name|Brief description of the property|object |
|neighbourhood|Neighborhood name|object |
|number_of_reviews|How many reviewers? |int64  |
|review_scores_rating|Reviewer ratings out of 100|float64|
|thumbnail_url|An image to show the property when browsing between properties|object |
|zipcode|Postal code|object|
|bedrooms|Number of bedrooms|float64|
|beds|Number of beds|float64|

## Tools
Jupyter Notebook

Language: Python

Libraries: numpy, pandas, seaborn, Plotly, matplotlib

## Models

machine learning models: 

Linear Regression, 
Lasso Regression,
Ridge Regression,
Decision Tree Regression,
Random Forest Regression,
xgboost Regression 
## Installation

Run pip install command to install related packages.

```bash
!pip install numpy
!pip install pandas
!pip install seaborn
!pip install Plotly
!pip install xgboost
```
    
## Questions
1. What are the most income cities ?

2. What is the most expensive neighborhood?

3. What type of property is most in demand?

4. What type of room is most requested?

5. What is the percentage of the cleaning fee?

6. What is the policy ratio?
## MVP

Knowing some of the clients' interests in housing. 
## Dataset_Resource

https://www.kaggle.com/stevezhenghp/airbnb-price-prediction
## Author

[@YasserMohammedK](https://github.com/YasserMohammedK) 

[@aamalsabr1](https://github.com/aamalsabr1)

[@Rahaf-t25](https://github.com/rahaf-t25)
