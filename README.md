# FIFA-22-player-analysis

## Introduction
This project analyzes data on the players in the Career mode for FIFA 22. The dataset was gotten from [kaggle](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset) and contains 19000+ players and 110 columns that represents different attributes of the players. Some of the columns are age, preferred foot, height, weight, nationality, club and a lot more columns that rate players on different skills.

In this project, I also implemented a KMeans clustering algorithm in order to cluster players according to their positions; Forwards, Midfielders, Defenders and Goalkeepers. I created an algorithm using python and pandas then compared the results to an implementation using scikit-learn.

## Data Wrangling
The dataset was cleaned for the most part. There were no null values for most of the well known players.

## Data Exploration
Here, I investigated some of the player attributes in order to get familiar with the dataset and see if there was any interesting finding.

## Observations
* Age distribution shows that players are typically around **20 to 30 years** old.
* Height distribution shows that players are generally around **170 to 190 cm** tall.
* Weight distribution shows that players generally weigh around **65 to 85 kg**.
* **76.3%** of players prefer using **right foot** to play.
* **Manchester City** has the most number of players, **11**, in the top 100 overall rated players.
* The runtime of a movie has a weak positive correlation of **0.26** with the revenue.
* The Drama genre produces more movies yearly than any other genre. Average popularity among genres is really close between Animation, Adventure and Science Fiction year to year.
* Walt Disney Pictures has the highest average revenue generated among production companies. With an average revenue of **247 million dollars**, the next best company (Twentieth Century Fox Film Corporation) averages **167 million dollars** in revenue.
* There is a strong positive correlation of **0.76** between vote count and Revenue.

## Limitations
* Correlation does not imply causation. This analysis merely tests the correlation between two variables and does not imply that one variable causes change in the other. Several other statistical methods and tests have to be run before one can come to a conclusion of causation.
* Missing values in the revenue columns can be researched and filled in to make a more complete dataset.
* The cast column contained very weird strings that made exploring it a bit difficult.
* This dataset is a sample of all the movies ever produced. Some insights may change if this analysis were done with another sample of the population dataset.
