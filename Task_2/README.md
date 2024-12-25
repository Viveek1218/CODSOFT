# Movie Rating Prediction with Machine Learning

## **Objective:**

The objective of this project is to analyze historical movie data and develop a machine learning model that accurately estimates the rating given to a movie by users or critics. This can be valuable for stakeholders in the movie industry to make informed decisions regarding film production, marketing strategies, and audience targeting.

## **Dataset:**

The project uses the "IMDb Movies India" dataset. This dataset contains information about Indian movies, including their titles, genres, directors, actors, release years, durations, ratings, and votes. The dataset is publicly available and can be downloaded from various sources. You can find it in this repository under the name `IMDb Movies India.csv`.

## **Data Cleaning and Preprocessing:**

The following steps were taken to clean and preprocess the data:

1.  Handling Missing Values: Rows with missing values were removed to ensure data quality.
2.  Handling Duplicates: Duplicate rows were removed to avoid redundancy.
3.  Data Type Conversion: Columns like 'Year', 'Duration', and 'Votes' were converted to their appropriate data types (numeric) for analysis.

## **Exploratory Data Analysis (EDA):**

EDA was performed to gain insights into the data. This involved:

1.  Descriptive Statistics: Calculating summary statistics for numerical features to understand their distributions.
2.  Data Visualization: Creating histograms and bar plots to visualize the distributions of ratings, genres, directors, and actors.
3.  Correlation Analysis: Examining the relationships between numerical variables using a correlation matrix and pair plots.

## **Feature Engineering:**

New features were engineered to improve model performance:

1.  Average Ratings: Calculated average ratings for each genre, director, and actor, and added them as new columns.
2.  Handling Missing Averages: Missing average ratings were filled with the movie's own rating.

## **Model Selection and Evaluation:**

Two models were built and evaluated:

1.  Linear Regression
2.  Random Forest Regressor

The Random Forest Regressor model outperformed the Linear Regression model, achieving an R-squared (R2) score of 0.812. This indicates that the model can explain approximately 81.2% of the variance in movie ratings.

## **Summary:**

This project successfully developed a machine learning model for predicting movie ratings using the "IMDb Movies India" dataset. The Random Forest Regressor model emerged as the most accurate predictor, demonstrating its potential for practical applications in the movie industry. Further research and model refinement can enhance its predictive capabilities.
