# Web Scraping Ecommerce sites using Selenium & Python

This repository contains all the code to extract and analyse product data from 2 largest E-commerce platforms in Hong Kong and US - HKTVmall & Amazon respectively, for explorations of potential business opportunites.

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/intro.png" width="800"/>

### Business Value of this Project

- Identifying new opportunities
  - Are there in-demand products that are under-supplied? Are there new audiences to target?
- Understanding Customer Needs
  - What do our customers want? How can we better cater to their needs?
- Determining Growth Factors
  - What are the biggest drivers of e-commerce sales?

### Project Overview

- Web scraped over 50,000 skincare products from HKTVmall and Amazon and preprocessed the data for analysis
- Constructed data frames and visualisations which identified gaps in the market and analysed consumer spending habits such as price elasticity of demand and effective types of promotions
- Made appropriate business recommendations according to the data-driven market insights

## What is in this repo?

- `Notebooks with 01-04` are the complete steps - from web-scraping, data preprocessing, merging datasets to visualization.
- `dataframes` contains csv files that store the cleaned product data.
- `img` contains illustrations for this README.md
- `EcommerceAnalysis.pdf` is a powerpoint which illustrates the complete framework of this project. 

## Data Collection & Preprocessing

We collected the product data from HKTVmall and Amazon through webscraping with Selenium and Beautiful Soup, instead of API. API of HKTVmall is not for public use, makes it even harder than sraping to complete data acquisition.

We executed some common preprocessing steps, and engineered new features at a later point to improve our analytical accuracy.

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/data-preprocessing.png" width="800"/>

## Key Findings

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana01.png" width="800"/>

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana02.png" width="800"/>

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana04.png" width="800"/>

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana05.png" width="800"/>

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana06.png" width="800”/>

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/ana07.png" width="800"/>

## Business Recommendations

<img src="https://github.com/sophiachann/WebScrapingProject-EcommerceAnalysis/blob/main/img/bus-recommendations.png" width="800"/>
