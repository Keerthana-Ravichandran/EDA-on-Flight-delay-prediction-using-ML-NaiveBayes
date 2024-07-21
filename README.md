# EDA-on-Flight-delay-prediction-using-ML-NaiveBayes



Predicting flight delays can be useful to a variety of organizations: airport authorities, airlines, and aviation authorities. At times, joint task forces have been formed to address the problem. If such an organization were to provide ongoing real-time assistance with flight delays, it would benefit from some advance notice about flights that are likely to be delayed.

In this simplified illustration, we look at five predictors, or features (see table below). The outcome of interest is whether or not the flight is delayed. Our data consist of all flights from the Washington, DC area into the New York City area during January 2004. A record is a particular flight.

The goal is to accurately predict whether or not a new flight, will be delayed. The outcome variable is whether the flight was delayed, and thus it has two classes (1 = delayed and 0 = on time).

**Feature	Description**
Day of the Week	Coded as 1 = Monday, 2 = Tuesday, ..., 7 = Sunday
Departure Time	Divide into blocks of 1 hour each (Remove the minutes in the file and just retain the hour. Use Excel function)
Origin	Three airport codes: DCA (Reagan National), IAD (Dulles),
BWI (Baltimore–Washington Int’l)
Destination	Three airport codes: JFK (Kennedy), LGA (LaGuardia), EWR (Newark)
Carrier	Eight airline codes: CO (Continental), DH (Atlantic Coast), DL (Delta),
MQ (American Eagle), OH (Comair), RU (Continental Express),
UA (United), and US (USAirways)

Divide the data (2199 rows) into 2 data sets. Training Dataset (2100 records) and Validation Dataset (99 rows)
Use training data to train the Naïve Bayes’ Model. 
Test the trained model on the validation dataset. Figure out the ability of the model to predict the outcome, using the Validation Data Set. 


