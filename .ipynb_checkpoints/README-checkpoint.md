## Executive Summary:
There are many internet services available. To increase revenue, ISPs need to retain members for as long as possible . Getting new customers is not valuable if their customers are churning after a short period of time. 

## Problem Statement
One of the biggest problems Internet Service Providers face is retaining longterm customers as there is so much competition right now. Finding a way to retain these customers can be difficult. Some customers opt to pay month-by-month, some opt for contracts. The lying problem is finding the perpetrators  as to why these customers give up their service after a short period of time. The goal is to find what these factors are. Though it may be easy to assume customers may churn due to internet speeds or lacking products, we need to know based on their actual accounts, the factors that cause this. Having a model to automate this will save much time in analyzing the data.

## Objectives:

- Identify customer profiles that are likely to churn
- Find a way to reduce overall churn rate

## Key Findings:

- Customers with 2.5+ year contracts do not churn at all
- Customers with a contract churned 90% of the time as opposed to 55% with no contract
- Customers with a TV subscription churned 10% of the time
- Customers with Movie Package Subscription churned 34% of the time

## Data Dictionary:

- id: unique customer identification number
- is_tv_subscriber: customer is or is not a tv subscriber
- is_movie_package_subscriber: wether or not customer has a movie package subscription
- subscription_age: age of internet service subscription in years
- bill_avg: avg monthly bill
- remaining_contract: number of years remaining in contract suctomer must commit to otherwise pay a penalty
- download_avg: average downloads in GB
- upload_avg: average uploads in GB
- download_over_limit: if customer went over their download limit within the contract
- churn: wether or not customer has cancelled their internet service wether contract or month-to-month subscription

## Sources:
Dataset from https://www.kaggle.com/mehmetsabrikunt/internet-service-churn/metadata