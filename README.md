# Data-Scientist-Capstone-Project
Data Scientist Nanodegree
## Starbucks Capstone Challenge


## Table of Contents

[Introduction](#installation)

[Project Motivation](#project-motivation)

[File Descriptions](#file-descriptions)

[Results](#results)

[Acknowledgements](#acknowledgements)

## Introduction
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. In this project, I will understand the data and try to provide a solution for how Starbucks should deal with customers, which promotions should provide and to whom? instead of providing offers for all customer which that make the customers who completed offers feel better and may push them to be customers for a long time.<br>
I will combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type.<br>

## Project Motivation
In this project, I will analysis the datasets provided by answering these questions  which help to make a decision to solve the problem with visualizations and modeling the dataset:<br>
* Q1: What is the distribution of gender?<br>
* Q2: What is the distribution of income?<br>
* Q3: What is the distribution of income by gender?<br>
* Q4: Which the most year that the customers created an app account?<br>
* Q5: What are the most and the least common event?<br>
* Q6: What are the most and the least common offer type?<br>
* Q7: What are the most and the least common offer type by offer completed?<br>
* Q8: What is the distribution of gender by offer type?<br>
* Q9: What is the distribution of gender by event?<br>

Then, I will calculate the accuracy metrics for some of the models on the training and testing datasets and improve the best one.<br>

## File Descriptions
The data is contained in three files:<br>

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)<br>
  * id (string) - offer id <br>
  * offer_type (string) - type of offer ie BOGO, discount, informational<br>
  * difficulty (int) - minimum required spend to complete an offer<br>
  * reward (int) - reward given for completing an offer<br>
  * duration (int) - time for offer to be open, in days<br>
  * channels (list of strings)<br>
* profile.json - demographic data for each customer<br>
  * age (int) - age of the customer<br>
  * became_member_on (int) - date when customer created an app account<br>
  * gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)<br>
  * id (str) - customer id<br>
  * income (float) - customer's income<br>
* transcript.json - records for transactions, offers received, offers viewed, and offers completed<br>
  * event (str) - record description (ie transaction, offer received, offer viewed, etc.)<br>
  * person (str) - customer id<br>
  * time (int) - time in hours since start of test. The data begins at time t=0<br>
  * value - (dict of strings) - either an offer id or transaction amount depending on the record<br>
  
## Results

The main findings of the code can be found at the post available [here]().

## Acknowledgements

Many Thanks for Starbucks to give this dataset available. I found the Licensing for the data and other descriptive information at Udacity. 

