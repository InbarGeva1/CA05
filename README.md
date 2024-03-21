# CA05

## **Overview**
This project uses a k-Nearest Neighbors (k-NN) based recommender system to suggest movies similar to a given query. The idea is to replicate the fundamental mechanisms behind recommender systems used by platforms like Netflix and IMDb on a smaller scale. Given a movie, the system finds and recommends the top 5 movies similar to it based on genre classifications and IMDb ratings.

## **Data Source**
The recommender uses a subset of movie data extracted from the UCI Machine Learning Repository's IMDb dataset. This dataset includes thirty movies, across seven genres, alongside their IMDb ratings.

Data File: movies_recommendation_data.csv
Source URL:  https://github.com/ArinB/MSBA-CA-
Data/raw/main/CA05/movies_recommendation_data.csv

## **Features**

Uses k-NN algorithm to find movies similar to a given movie.
Uses both Euclidean and Manhattan distance metrics for determining similarity.
Includes a visualization of the feature space showing the query movie, its features, and its nearest neighbors.

## **Requirements**
This project is implemented in Python, utilizing libraries such as
- Pandas for data manipulation,
-  NumPy for numerical operations,
-  Matplotlib for visualization, 
-  sklearn for the k-NN algorithm.

##To install the necessary libraries, run:

- pip install 
- pandas numpy 
- matplotlib scikit-learn

## **Usage**
Copy this repository to your local machine.
Make sure you have Python and the necessary libraries installed.
Run the Jupyter Notebook CA05.ipynb to see the codes and results.

Example Query
To find movies similar to "The Post", the system uses the following feature vector based on its IMDb rating and genre presence:

IMDB Rating = 7.2, Biography = Yes, Drama = Yes, Thriller = No, Comedy = No, Crime = No, Mystery = No, History = Yes

