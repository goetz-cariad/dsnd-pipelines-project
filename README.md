# NLP Pipeline Project
A project from the [udacity Data Scientist nanodegree](https://www.udacity.com/blog/2018/05/introducing-udacity-data-scientist-nanodegree-program.html).  
We start with a dataset of reviews and set up a natural language processing pipeline to analyse and predict if the customer recommends a product based on the review.

## Date created
March 12 2026

## Motivation / Scenario
You've recently joined "StyleSense", a rapidly growing online women's clothing retailer, as a data scientist. StyleSense is known for its trendy and affordable fashion, and its customer base has exploded in recent months. This influx of new customers is fantastic for business, but it has created a challenge: a backlog of product reviews with missing data. Customers are still leaving valuable feedback in the text of their reviews, but they aren't always indicating whether they recommend the product.

Your first task at StyleSense is to leverage the existing data– those reviews with complete information – to build a predictive model.

This model will analyze the text of a review, the customer's age, the product category, and other relevant information to predict whether or not the customer would recommend the product. By automating this process, you'll help StyleSense gain valuable insights into customer satisfaction, identify trending products, and ultimately provide a better shopping experience for their growing customer base.

The future of fashion forecasting is in your hands!

## Features
- Pipeline distinguishes numerical, categorical and text data
- Sentiment Analysis based on pretrained model
- Random Forest Classifier to predict recommendation


## Getting started
### Prerequisites
- Python >= 3.13.7
- (Jupyter) notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- spacy
- torch
- transformers
- scipy
- joblib
(exact versions for packages to be found in requirements.txt)

### Installation
1. Clone the repo:
    ``` git clone <repository-url> ```
2. Install the requirements
    ``` pip install requirements.txt ```
3. the /models folder is optional. It contains the pretrained pipeline components.  
If the pipeline should be trained from scratch either delete the models or set the ***retrain*** variable in the includes and installs chapter to **True**.


## Files
- nlp_pipeline.ipynb - The main Jupyter notebook containing all code and comments
- requirements.txt - necessary python libraries to install
- /data folder containg
    - raw data file (reviews.csv)
- /model folder containing
    - pretrained pipeline components (feature_engineering.pkl, random_forest.pkl, best_forest.pkl)
    - transformed training data (X_train_transformed.npz)


## Acknoledgements
- Credits for setting up this challenge go to the [udacity](https://www.udacity.com/) team.
