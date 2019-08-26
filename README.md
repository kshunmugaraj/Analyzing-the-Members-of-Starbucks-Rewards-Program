## Analyzing the Members of Starbucks Rewards Program

### Table of Contents

1. [Project Overview and Motivation](#motivation)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

All libraries are avilable in Anaconda distribution of Python.  The code should run using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

Coffee is one of the most popular drinks in the world. Drinking a cup of coffee is the first thing millions of people start their day with because it provides the body with an energy boost. According to a recent research on coffee, around 2.25 billion cups of coffee are consumed around the world annually. In the United States, there are more than 21,400 coffee shops. Starbucks coffee shop is one of the most famous coffee shops in the world which has 24,000 stores.
Starbucks always focus on satisfying their customers and make them feel happy. Starbucks does this by knowing their names and their previous orders. Additionally, Starbucks is always creating new ideas to get the customer feedback. Starbucks seeks to satisfy their loyal customers by ‘Starbucks Rewards’ program. Starbucks rewards program is a loyalty programs which offers freebies and discounts to the members. The customers can join the rewards program using Starbucks rewards mobile app. The mobile app provides the customers with offers and allows the customer to collect stars and earn rewards. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free).
To satisfy the customers and keep the business running, the customers interaction with the offers should be investigated. The goal of this blog is to investigate the Starbucks customers interaction with the offers by analyzing a simulated data that mimics customer behavior on the Starbucks Rewards mobile app. The analysis answers four main questions:

1.	Will the customer respond to the offer?
2.	Which offer should be sent to the customer?
3.	Which customers view offers?
4.	Which customers paid more money? 


## File Descriptions <a name="files"></a>

	- One notebook file `Starbucks_Capstone_notebook.ipynb` which contains the code. 
	- portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
	- profile.json - demographic data for each customer
	- transcript.json - records for transactions, offers received, offers viewed, and offers completed. This file is zipped because it is big. 


## Results<a name="results"></a>

The finding can be summarized as follows:
1.	The offers that use the four types of channels have bigger number of transactions than the other offers. 
2.	The customers who are between 18 and 45 years old are more likely to respond to offers than the older customers. 
3.	The customers who have incomes between $35000 and $70000 are more likely to respond to offers than the richer customers.
4.	The customers with incomes 35000 - 85000 response to discount offer more than BOGO.
5.	65.07% of the offers are not viewed and only 24.38% of the viewed offers are completed. 
6.	The customers view more BOGO offers than discount offers. 
7.	Females are more likely to view the offers than males. 
8.	The total amount of money paid by females is $863695 and by males is $844890.86.
9.	 BOGO offer made a highest amount of money than discount offer.

The findings also is available [here](https://medium.com/@alay.nada/analyzing-the-members-of-starbucks-rewards-program-562f263a878c?sk=3e6598fa6d579f2610074e4faf553ade).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

This project is part of Udacity's Data Scientists Nanodegree Program. The datasets are provided Udacity. 
