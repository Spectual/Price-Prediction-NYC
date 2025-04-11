# Price Prediction (Housing Rental)

## Overview

🏠 Airbnb NYC Price Prediction

Pricing short-term rental properties accurately is a crucial challenge for platforms like Airbnb. With so many variables affecting price—such as location, amenities, host reputation, and guest reviews—it’s not always easy to know what a listing should cost.

In this competition, your goal is to build a machine learning model that predicts the log-transformed price of Airbnb listings in New York City using a rich set of features. The dataset contains nearly 30,000 listings and over 750 features, ranging from host characteristics to neighborhood identifiers and listing details.

Participants will use this dataset to train and evaluate models that can accurately estimate the price of unseen listings. A strong model could help both hosts and guests make more informed decisions.



💡 Objective
Develop a regression model that predicts the log(price) of NYC Airbnb listings based on listing attributes.



### Description

This dataset has already undergone initial cleaning and processing, which includes:

Handling missing values
Converting textual data into categorical or numerical formats
One-hot encoding location-based fields
Performing sentiment analysis on user reviews (comments column)
The target variable is the logarithm of the price, meaning models should be trained to predict values in a range roughly between 2.3 and 9.2 (corresponding to real-world prices from around $10 to $10,000).

📊 The Dataset

You will work with a dataset containing:

Nearly 30,000 listings
764 features including:
Host attributes (e.g., host_is_superhost, host_response_rate)
Location data (latitude, longitude)
Property characteristics (bathrooms, accommodates, room_type)
Sentiment-encoded reviews (comments)
One-hot encoded neighborhood and borough information
Example feature columns:

host_since, host_identity_verified, accommodates, bathrooms
Williamsburg.1, Woodside.1, Harlem.1 (neighborhood encodings)



### Evaluation

Submissions are evaluated based on Mean Squared Error (MSE) between your predicted values and the actual log-transformed prices in the test set.

A lower MSE indicates better model performance.