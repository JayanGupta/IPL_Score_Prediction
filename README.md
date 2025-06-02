# IPL Score Prediction

This project builds a machine learning model to predict the final score of an IPL (Indian Premier League) cricket match innings based on match progress and real-time data. The prediction can help fans, analysts, and broadcasters estimate the likely final score during the match.

## Project Overview

The IPL Score Prediction model takes key match factors such as runs scored, wickets lost, overs bowled, current run rate, and other derived metrics to predict the final innings score. The model uses historical IPL match data for training and applies regression techniques for prediction.

## Features

- Data preprocessing and feature engineering from raw IPL match data
- Exploratory data analysis with visualizations
- Model training using Linear Regression
- Evaluation of model performance with metrics like R-squared and error analysis
- Final score prediction based on partial match data input

## Dataset

The dataset used consists of IPL match ball-by-ball data, including:

- Runs scored per ball
- Wickets fallen
- Overs and balls bowled
- Match and innings identifiers

The data is processed to extract relevant features and target values for model training.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ipl-score-prediction.git
   cd ipl-score-prediction
