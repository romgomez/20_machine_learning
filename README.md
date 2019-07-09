# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

In this homework assignment, you will need to:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

### Preprocess the Data

* Preprocess the raw dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features. The dataset includes 50 columns-- how many will be sufficient for a healthy model?
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers. Three is recommended.

### Evaluate Model Performance

Compare the performance of your tuned classifiers to determine the best-performing model.

- - -

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

* [Scikit-Learn Tutorial Part 1](https://www.youtube.com/watch?v=4PXAztQtoTg)

* [Scikit-Learn Tutorial Part 2](https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

* [Grid Search](https://scikit-learn.org/stable/modules/grid_search.html)

- - -

## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* For each ML algorithm, try a simple model first, and then tune the model using `GridSearch`; if you choose to use deep learning, try different activation functions and number of nodes, layers, etc. (you will need to do this manually).

- - -

## Submission

* Create a Jupyter Notebook and host the notebook on GitHub.

* ***Include a README.md file that summarizes your assumptions and findings.*** Try to include as many visualizations as possible, visualizing the distribution of your features and your models' accuracies.  

* Submit the link to your GitHub project to Bootcamp Spot.
