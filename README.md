# Car-Crashes-Severity-Prediction
Exploratory data analysis and machine learning model development of nationwide dataset on San Francisco.

# Goals
The goal of this project is to investigate trends in U.S. car accidents and use it to develop a machine learning regression model that will predict the severity of collision if it were to occur in a particular city. Severity is defined within a range of integers, 1 to 4 and which represent the following:

1 - Short Delay
2 - Manageable Delay
3 - Extended Delay
4 - Long Delay

# Data Source
Bata about car crashes severity. The file contains 16 features, it represents the car crashes in the city of San Francisco between 2016 and 2020.

# File descriptions
train.csv - the training set.
holidays.xml - Information about whether the day is a regular day or a holiday.
weather-sfcsv.csv - Information about the weather.
test.csv - the test set.
sample_submission.csv - a sample submission file in the correct format

# Data fields
Lat - Latitude of the incident
Lng - Longitude of the incident
Bump, Crossing, Give_Way,Junction, NoExit, RailWay, Roundabout, Stop, Amenity, Side - The characteristics of the location where the incident has taken place, several can be true at the same time. Side is the side of the street.
State - the state from which this dataset is coming from
Distance - the distance of the traffic jam provoked by an accident
Timestamp - the moment when the incident has occurred.
Severity - (Target) An indicator representing the severity of the car crash and possible impacts on the traffic. Values can range from 1 to 4, the highest value translates a highest impact.
Severity is the target variable for that exercise. The target variable is the one we want to predict thanks to the predictive system module already present that you will build during that Programming Challenge.
