# Predicting the best Sephora skincare product based on customer physical attributes
## DSCI 303: Machine Learning for Data Science
Authors: Joshua Fang and Huijun Mao

## Table of Contents
1. [Project Description](#project-description)
2. [Prerequistes](#prerequistes)
3. [Folder Structure](#folder-structure)
4. [Installation & Usage Instructions](#installation-&-usage-instructions)
5. [Dataset](#dataset)

## Project Description
Our goal is to create a recommender system by training models to predict the best Sephora skincare product based on customer physical attributes. For now, we focus on moisturizers only. If time permits, we will add other skincare product categories, like sunscreen, to create a more comprehensive recommender system.

## Prerequisites
- Matplotlib
- Seaborn
- Numpy
- Pandas
- Scikit-learn
- os
- warnings

## Contents
sephora.ipynb: this is the Jupyter Notebook used to generate all results.
READ.md: this file provides directions on how to obtain the data and run the code.

## Installation & Usage Instructions
1. Download the data from https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews to the your local machine. 
2. Extract all contents of archive.zip.
3. Clone repository to your local machine: <br>
`git clone https://github.com/RiceD2KLab/sephora.git
4. Install dependencies with the following commands:
```
pip install matplotlib
pip install seaborn
pip install numpy
pip install pandas
pip install scikit-learn
pip install os
pip install warnings
```
5. Execute the code provided in sephora.ipynb as required. 

### Datasets
Source: https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews

This dataset was collected via Python scraper in March 2023 and contains:

* information about all beauty products (over 8,000) from the Sephora online store, including product and brand names, prices, ingredients, ratings, and all features.
* user reviews (about 1 million on over 2,000 products) of all products from the Skincare category, including user appearances, and review ratings by other users
