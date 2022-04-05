# Basket Analysis with Association Rule Learning

![image](https://user-images.githubusercontent.com/83332641/161730709-26f185b0-18e0-4a70-813d-69625bcd0d6b.png)


## Table of contents
* [Introduction](#Introduction)
* [Context](#Context)
* [Business Problem](#Business_Problem)
* [Attribute Information](#Attribute_Information)
* [Task Details](#Task_Details)

## Introduction

Association Rule Learning (ARL) is a rule-based machine learning method for discovering interesting relationships between variables in large databases.

ARL Algorithm can be used in different fields, here we will focus on Basket Analysis. Basket Analysis with ARL is one of the most popular techniques for identifying offers that increase overall sales and finding the best product placement in the store.

The idea is to bring together a set of products that have some sort of relationship between them and increase sales by reminding customers of their need for the relevant product.

## Context

The dataset named Online Retail II was obtained from a UK-based online store and includes sales from 01/12/2009 to 09/12/2011.

This company sells souvenirs and most of their customers are also wholesalers. Within the scope of this study, only 2010-2011 sales will be consedered.

## Business Problem

Our aim is to apply association analysis to the online retail II dataset and to offer suggestions based on the products in their baskets to users who are in the process of purchasing products.

## Attribute Information:

**InvoiceNo:** Invoice number. The unique number of each transaction, that is, the invoice. Aborted operation if it starts with C.  
**StockCode:** Product code. Unique number for each product.  
**Description:** Product name  
**Quantity:** Number of products. It expresses how many of the products on the invoices have been sold.  
**InvoiceDate:** Invoice date and time.  
**UnitPrice:** Product price (in GBP)  
**CustomerID:** Unique customer number  
**Country:** Country name. Country where the customer lives.  

## Task Details

* Data Preprocessing  
* Preparing the ARL Data Structure (Invoice-Product Matrix)  
* Extracting Association Rules  
* Suggesting a Product to Users at the Basket Stage  


