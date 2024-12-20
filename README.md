Predictive Maintenance
Introduction:
This project has been done in fulfillment to the First Capstone Project requirement of Springboard Data Science Career Track Bootcamp. The work on the project was mentored by Alex Chao.

The project objective is to enhance the maintenance operations and planning of time-based preventive maintenance by applying data science techniques and machine learning algorithms for predicting more accurate maintenance requirements.

Problem:
Failure prediction is a major topic in predictive maintenance in many industries. Airlines are particularly interested in predicting equipment failures in advance so that they can enhance operations and reduce flight delays.

Observing engine's health and condition through sensors and telemetry data is assumed to facilitate this type of maintenance by predicting Time-To-Failure (TTF) or Remaining Useful Life (RUL) of in-service equipment. Using aircraft engine's sensors measurements, The project attempt to provide the following predictions:

engine's TTF
which engines will fail in the current period or cycle window
maintenance plan based on prediction of engines failure per period
Data:
Text files contain simulated aircraft engine run-to-failure events, operational settings, and 21 sensors measurements are provided by Microsoft. It is assumed that the engine progressing degradation pattern is reflected in its sensor measurements.

Training Data: The aircraft engine run-to-failure data. download trianing data
Test Data: The aircraft engine operating data without failure events recorded. download test data
Ground Truth Data: The true remaining cycles for each engine in the testing data. download truth data

Approach:
By exploring the aircraft engine’s sensor values over time, the machine learning algorithm can learn the relationship between the sensor values and changes in sensor values to the historical failures in order to predict failures in the future.

Regression Modeling algorithms were used to predict the number remaining cycles before engine failure.
Binary Classification algorithms were used to predict if the engine will fail within specific cycles window or not
Multiclass classification algorithms were used predict in which cycles window or period will an engine will fail.
Project Files:
README
Project Proposal
Data Wrangling
Exploratory Data Analysis
Regression Modeling
Binary Classification
Multiclass Classification
Final Project Report
Project Summary - Slide Decks
Project Data Folder
Project Figures Folder
