# Analysis using NLP on Google Play Store Reviews
## Overview
This repository contains files and data related to the analysis of Google Play Store reviews using Natural Language Processing (NLP). The analysis primarily focuses on sentiment analysis, utilizing machine learning techniques for model preparation.

## Files
### 1) Automated PlayStore review scraping.ipynb: 
This Jupyter Notebook file is used for scraping reviews from the Google Play Store. It contains the code and process for collecting the raw data.

### 2) NLP Automation.ipynb: 
This Jupyter Notebook file focuses on the automation of Natural Language Processing tasks. It includes the following preprocessing steps:
- Changing to Lower-case: Convert all text to lowercase for consistency.
- Remove Numbers: Eliminate numerical characters from the text.
- Remove Punctuations: Get rid of punctuation marks in the text.
- Remove Stopwords: Remove common words (stopwords) that do not contribute much to the meaning.
- Remove URL/https: Eliminate URLs or any hyperlinks present in the text.
- Lemmatization: Reduce words to their base or root form.
- Remove Common Words: Further removal of common words that may not add significant value.
- Remove Extra White Space: Ensure uniform spacing in the text.

Further, this cleaned data is used for sentiment analysis to gain insights into the sentiments expressed in the Google Play Store reviews.  

### 3) Machine Learning on NLP Data.ipynb: 
This Jupyter Notebook file involves the machine learning aspect of the analysis. It utilizes the NLP data to train and evaluate models.

### 4) build.pkl: 
This file stores the trained machine learning model in a serialized format. It can be loaded for predictions without the need to retrain the model.

### 5) DataSet folder: 
This folder contains datasets fetched from the Google Play Store. There are four different datasets from MakeMyTrip, Goibibo, Booking.com & Yatra platforms, all collected for sentiment analysis.

### 6) Sentiment Dataset: 
This folder contains the output dataset generated from the sentiment analysis. It serves as the labeled data for model training in the "Machine Learning on NLP Data.ipynb" file.

## How to Use
### 1) Scraping Reviews: 
Execute the code in the "Automated PlayStore review scraping.ipynb" notebook to scrape reviews from the Google Play Store. Ensure to store the raw data in the appropriate format.

### 2) NLP Automation: 
Explore the "NLP Automation.ipynb" notebook for automated NLP tasks, including comprehensive preprocessing steps for cleaning the text data.

### 3) Machine Learning Model Preparation: 
Run the code in the "Machine Learning on NLP Data.ipynb" notebook to train machine learning models using the NLP data and sentiment dataset.

### 4) Model Deployment: 
Use the "build.pkl" file to deploy the trained machine learning model for making predictions on new data.

### Note
Ensure to follow ethical guidelines and terms of service while scraping data from the Google Play Store. Respect user privacy and adhere to applicable regulations.
