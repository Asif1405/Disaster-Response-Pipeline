# Disaster-Response-Pipeline

# Overview
In this project, using data engineering and NLP skills to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages. 

# Instruction
Run the following commands in the project's root directory to set up your database and model.

1. To run ETL pipeline that cleans data and stores in sql database: python pipelines/process_data.py pipelines/disaster_messages.csv pipelines/disaster_categories.csv pipelines/DisasterResponse.db
2. To run ML pipeline that trains classifier and saves the model: python pipelines/train_classifier.py pipelines/DisasterResponse.db pipelines/classifier.pkl

Run the following command in the app's directory to run your web app: python run.py

Go to http://0.0.0.0:3001/ to check out the API.

# Packages

1. Flask
2. NLTK
3. numpy
4. plotly
5. pandas
6. sklearn
7. sqlalchemy

# Files

1. pipelines/disaster_messages.csv pipelines/disaster_categories.csv : original data
2. pipelines/process_data.py: to run ETL pipeline that cleans data and stores in database
3. pipelines/train_classifier.py: to run ML pipeline that trains classifier and saves
4. app/: a Flask framework for presenting data
