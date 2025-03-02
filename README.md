# MSDS-5509-Final-Project
Final supervised learning project for MSDS course 5509.

This project uses supervised learning techniques to predict running pace based on personal Garmin activity data. 
The goal is to determine which factors best predict avgSpeedMinMile using machine learning models.

## Data
The data was obtained through a request to Garmin for my personal data. Sensitive data (my location) was removed prior to analysis. The initial dataset was all of my Garmin activities from 2018 through 2024, and included 94 columns and 2,347 rows. Columns included both metrics that related to running such as duration, distance, and elevationGain and metrics that did not such as strokes, poolLength and totalReps. The dataset itself is not included in the repository.

## Models Used & Evaluation
-Decision Tree Regressor

-Random Forest Regressor

Evaluation Metrics:
R-squared and Mean Squared Error were calculated on the testing set.
Based on these metrics, the Random Forest produced the best fitting model.

## Future Improvements
Improvements to this would include incorporating weather conditions and/or experimenting with additional models.
