# Disaster Response Pipeline Project

## Project Motivation
In this project I have used the skills I learned through data engineering to analyze disaster message data from Figure Eight to build a model for an API that classifies disaster messages.

Also, built a web app where an emergency worker can input a new message and get classification results in several categories

# Getting Started

## Dependencies

    Python 3
    Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
    Natural Language Process Libraries: NLTK
    SQLlite Database Libraqries: SQLalchemy
    Web App and Data Visualization: Flask, Plotly
    
## Executing Program:

    Run the following commands in the project's root directory to set up your database and model.
        To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
        To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

    Run the following command in the app's directory to run your web app. python run.py

    Go to http://0.0.0.0:3001/

