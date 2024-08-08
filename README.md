# Breast_Cancer_Analysis
Breast Cancer Data Analysis

## Project Overview

This project focuses on analyzing breast cancer data using machine learning techniques to build predictive models and visualize insights. The key objectives include data cleaning, feature selection, model building, and creating an interactive application for users.

## Data Description
The dataset used in this project contains breast cancer data, with various features related to the diagnosis and characteristics of the tumors.

## Setup Instructions
Prerequisites:

Python 3.7 or higher
Required Libraries:
pandas 
numpy 
scikit-learn 
tensorflow
streamlit 
matplotlib 
seaborn 

Install the required libraries:

pip install pandas numpy scikit-learn tensorflow streamlit matplotlib seaborn

## Code Description
## Python Scripts:

data_preprocessing.py: Handles data cleaning and preprocessing.
feature_selection.py: Selects important features for the model.
ann_model.py: Builds and trains an artificial neural network model.
model_building.py: Tunes model parameters for better performance.
Streamlit App:

app.py: A Streamlit application to visualize data insights and interact with the predictive model.
Running the Application
Prepare the data:
   python data_preprocessing.py



Select features:
python feature_selection.py

Train the model:
python ann_model.py


Tune the model:
python model_building.py

Run the Streamlit app:
streamlit run app.py

This setup will help you analyze the breast cancer data, build predictive models, and create interactive visualizations to gain insights from the data.
