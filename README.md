# Customer Segmentation in Python

## Course Description

The most successful companies today are the ones that know their customer so well that they can anticipate their needs. Data analysts play a key role in unlocking these in-depth insights, and segmenting the customers to better serve them. In this course, you will learn real-world techniques on customer segmentation and behavioral analytics, using a real dataset containing customer transactions from an online retailer. You will first identify which products are frequently bought together. Then, you will run cohort analysis to understand customer trends. On top of that, you will learn how to build easy to interpret customer segments. Finally, you will make your segments more powerful with k-means clustering, in just few lines of code! By the end of this course, you will be able to apply practical customer behavioral analytics and segmentation techniques.

### Traducción:

Las empresas más exitosas de hoy son las que conocen tan bien a sus clientes que pueden anticipar sus necesidades. Los analistas de datos desempeñan un papel clave en el desbloqueo de estos conocimientos en profundidad y en la segmentación de los clientes para atenderlos mejor.
En este curso, aprenderá técnicas del mundo real sobre segmentación de clientes y análisis de comportamiento, utilizando un conjunto de datos real que contiene transacciones de clientes de un minorista en línea. Primero identificarás qué productos se compran frecuentemente juntos. Luego, realizará un análisis de cohorte para comprender las tendencias de los clientes. Además de eso, aprenderá cómo crear segmentos de clientes fáciles de interpretar. Finalmente, hará que sus segmentos sean más potentes con el agrupamiento de k-means, ¡en solo unas pocas líneas de código! Al final de este curso, podrá aplicar técnicas prácticas de análisis de comportamiento y segmentación del cliente.

Link: [customer-segmentation-in-python](https://www.datacamp.com/courses/customer-segmentation-in-python)

### Previous definition

In statistics, marketing and demography, a cohort is a group of subjects who share a defining characteristic (typically subjects who experienced a common event in a selected time period, such as birth or graduation). Cohort data can oftentimes be more advantageous to demographers than period data. Because cohort data is honed to a specific time period, it is usually more accurate. It is more accurate because it can be tuned to retrieve custom data for a specific study. 

Source: [wikiedia](https://en.wikipedia.org/wiki/Cohort_(statistics)) 

## Dataset

### Source:

Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

### Data Set Information:

[Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/Online%20Retail)

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

### Attribute Information:

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.


## Chapter 1: Cohort Analysis

Understand customers based on their unique behavioral attributes. Cohort analysis provides deeper insights than the so-called vanity metrics. It helps with understanding the high level trends better by providing insights on metrics across both the product and the customer lifecycle.

## Chapter 2:  Recency, Frequency, Monetary Value analysis

Understand customers based on their unique behavioral attributes 

## Chapter 3: Data pre-processing for clustering

Learn practical data preparation methods to ensure the k-means clustering algorithm uncovers well-separated segments 

## Chapter 4: Customer Segmentation with K-means

Use data from previous chapter to build customer segments based on their recency, frequency, and monetary value 

## Prerequisites

- pandas library
- datetime objects
- basic plotting with matplotlib or seaborn
- basic knowledge of k-means clustering