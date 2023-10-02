## Project Explanation

### Introduction
In every data analysis project, we need a solid foundation to succeed. Such a foundation consists of specific steps that we need to perform necessary actions, gather the required information, and finally perform a well-structured and holistic data analysis.

### Problem Identification/ Problem Statement
In the first step, we should understand what exactly the problem is, which logic exists behind the problem, how it affects all the involved parties, and what clarified points of the main objective in the current data science project.

The main idea of this project is to extract actionable insights from the given data of a company that improves its decision-making process. Furthermore, we want to provide the best possible predictive model for the marketing campaign of their new product which shows if a customer buys the new product or not and how much is the possibility of the purchase.

### Data Description
The provided data is split into two CSV files containing the training (train.csv), and the test data (test.csv). The training date set includes 31480 records, containing customer and operational features. Customer features cover master data of customers such as their age, gender, occupation, marital status, education level, and account balance, while operational features are related to the last campaign activities including the last campaign result, contact date, contact duration, etc. The test date set consists of 13732 samples containing all the provided features in training data except the target value. In general, we have 19 features and one target variable that should be predicted. These features can be described as follows:

| Feature | Type | Description |
|---|---|---|
| id | Numerical | record ID |
| target | Object | target value (customer response to the marketing campaign) |
| day | Numerical | contact day in previous campaign |
| month | Object | contact month in previous campaign |
| duration | Numerical | contact duration in previous campaign |
| contactId | Numerical | contact ID |
| age | Numerical | age of the customer |
| gender | Object | customer gender |
| job | Object | customer occupation |
| maritalStatus | Object | customer marital status |
| education | Object | customer educational degree |
| craditFailure | Object | if the customer has a default credit |
| accountBalance | Numerical | customer account balance |
| house | Object | if the customer owns a house |
| credit | Object | if the customer has a credit |
| contactType | Object | contact media |
| numberOfContacts | Numerical | number of contacts during the current campaign |
| daySinceLastCampaign | Numerical | days after the last contact of the previous campaign |
| numberOfContactsLastCampaign | Numerical | number of contacts during the previous campaign |
| lastCampaignResult | Object | result of the previous campaign |
