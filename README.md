## Finding Items Bought Together

### Table of Contents

1. [Project Overview and Motivation](#motivation)
2. [File Descriptions](#files)
3. [Installation] (#installation)
4. [Results](#results)
5. [Licensing](#licensing)


## Project Motivation<a name="motivation"></a>
Customers are important to the survival and success of any business because they are the source of the revenue. The success of a business is the ability to satisfy customers and make them happy, and therefore turn a profit from them. Giving the customer recommendation about items that can buy it with items in their online basket may attract them. Using retail transactional data can help to build models for finding the items that are bought together and recommending customers about items that can buy it. 

In this project, I will analyze an online retail transactional dataset to answer the following questions:
1. Which items are bought together?
2. Which items are bought together in different specific countries?

To answer the questions, I will build an association rules model using Apriori Algorithm to find the items that are usually bought together by the customers. I will also find the items that are usually bought together in different specific countries.

## File Descriptions <a name="files"></a>
- One notebook file `Finding_Items_Bought_Together.ipynb` which contains the code. 
- One xlsx file `Online Retail.xlsx` which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for an online retail.
	
## Installation <a name="installation"></a>
All libraries are avilable in Anaconda distribution of Python except [mlxtend library](http://rasbt.github.io/mlxtend/installation/), you should install it. The code should run using Python versions 3.*.
 
## Results<a name="results"></a>
Apriori algorithm gave us some rules about the item that is frequently purchased with other items. The result of association analysis using the whole dataset different than the result of association analysis when using a dataset of a specific country. These rules are helpful for items recommendation in the e-commerce websites.

## Licensing <a name="licensing"></a>
The dataset is avilable in [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail) website. 
