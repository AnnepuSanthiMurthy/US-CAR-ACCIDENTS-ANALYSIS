USA Car Accident Analysis

Introduction

This repository contains analysis and insights derived from a comprehensive dataset of car accidents across 49 states of the USA. The data spans from February 2016 to March 2023 and includes approximately 7.7 million accident records. The dataset was collected using multiple APIs that provide streaming traffic incident data from various sources, including departments of transportation, law enforcement agencies, traffic cameras, and sensors.

Dataset Description

The dataset provides detailed information about car accidents, including:
Date and time of the accident
Location (latitude, longitude, state)
Weather conditions
Traffic conditions
Severity of the accident
Contributing factors (e.g., speeding, alcohol involvement)
For more information about the dataset, please refer to the original source here[https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents].

Repository Structure

├── data
│   ├── raw
│   ├── processed
├── notebooks
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_data_analysis.ipynb
│   ├── 04_visualizations.ipynb
├── src
│   ├── data_preprocessing.py
│   ├── analysis.py
│   ├── visualization.py
├── reports
│   ├── figures
│   ├── insights.pdf
├── README.md
├── requirements.txt
└── LICENSE

Getting Started
Prerequisites
Ensure you have Python 3.7 or later installed. You can install the required packages using:

pip install -r requirements.txt

Data
Raw Data: The raw data files should be placed in the data/raw directory.
Processed Data: The scripts in the src directory will process the raw data and save the cleaned data in the data/processed directory.
Notebooks
The Jupyter notebooks in the notebooks directory guide you through the different stages of our analysis:

01_data_exploration.ipynb: Initial exploration of the dataset.
02_data_cleaning.ipynb: Data cleaning and preprocessing steps.
03_data_analysis.ipynb: Detailed analysis to extract insights.
04_visualizations.ipynb: Visualization of the analysis results.
Scripts
data_preprocessing.py: Script for cleaning and preprocessing the data.
analysis.py: Script for conducting the analysis.
visualization.py: Script for creating visualizations.
Analysis and Insights
Key Findings
Accident Frequency: Analysis of accident frequency across different states and time periods.
Severity Analysis: Identification of factors contributing to the severity of accidents.
Weather Impact: Correlation between weather conditions and accident occurrences.
Traffic Conditions: Impact of traffic conditions on accident rates.
Visualizations
We have created several visualizations to illustrate our findings, including:

Heatmaps of accident locations.
Time-series analysis of accident trends.
Correlation matrices of contributing factors.
Conclusion
This analysis provides valuable insights into car accident trends and contributing factors across the USA. These findings can inform policy-making, improve traffic safety measures, and help in developing predictive models for accident prevention.

Contributors
Annepu Santhi Murthy
Manikanta
Sai krishna Varma
DVJK Raju


Acknowledgments
We thank the original data providers and all contributors who have made this analysis possible.

