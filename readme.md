## Glassdoor company review

# By Purvi Joshi

### Overview : 
This project is about text analysis where I have selected pros and cons of company from glassdoor reviews to perform analysis of what people are talking about companies both as pros and cons of company and perform hypotheis test about how people are happy or unhappy with companies from different cities and different companies from different features point of view like salary, managment, benefits,food,opputynity, company culture etc.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)



# Dataset - 
This dataset is taken from kaggle which is recenly uploaded and following 5 columns are used for analysis after merging 3 tables (glassdoor.csv,glassdoor_review.csv and glassdoor_benefits.csv):

        Column - Description - Datatype
  - id - company id - number
  - EmployerName - Name of company - String
  - City - City of company - String
  - pros - comments made by reviwer as pros of company - Text statements
  - cons - comments made by reviwer as pros of company - Text statements

# EDA

# Data Cleaning
- Filling missing values in pros and cons
- Convert pros and cons from object data type to string
    
# Feature selection
##### Performed following steps to select most frequent words from pros and cons:
- Tokenization
- Remove stop words
- Remove special charcters using Regular Expression
# Hypotheis testing
  - People of one city are equally happy with companies as people of another company
  - People of one city are equally un happy with companies as people of another company











   
