# Cyclone Trajectory Analysis and Prediction

This repository contains Jupyter notebooks for analyzing and predicting cyclone trajectories using MovingPandas and Variational Recurrent Neural Networks (VaRNN).

## Table of Contents
- Introduction
- Installation
- Data Preparation
- Trajectory Visualization
- Wind Speed Analysis
- Cyclone Frequency Analysis
- Detailed Cyclone Analysis
- VaRNN Model for Cyclone Prediction
- Results Analysis

## Introduction
This project focuses on the analysis and prediction of cyclone trajectories in the North Indian Ocean basin. It utilizes MovingPandas for trajectory analysis and visualization and implements a Variational Recurrent Neural Network (VaRNN) for cyclone track prediction.

## Installation
To run the notebooks, install the required dependencies for MovingPandas and the VaRNN model.

## Data Preparation
The project uses cyclone data from the North Indian Ocean basin. The data preparation steps include:
- Loading raw data from a CSV file.
- Converting timestamps to datetime objects.
- Sorting data by cyclone ID and timestamp.
- Implementing a segmentation algorithm to identify distinct cyclone tracks.

## Trajectory Visualization
Cyclone trajectories are visualized using MovingPandas and Matplotlib:
- Creating a GeoDataFrame from preprocessed data.
- Filtering for a subset of cyclone IDs.
- Generating a TrajectoryCollection.
- Plotting each trajectory with unique colors and markers for start/end points.
- Adding a basemap for geographical context.

## Wind Speed Analysis
A wind speed heatmap is created to visualize variations along cyclone trajectories:
- Randomly selecting cyclone IDs for analysis.
- Plotting trajectories with color representing wind speed.
- Adding a basemap and color bar for interpretation.

## Cyclone Frequency Analysis
The frequency of cyclones over the years is analyzed:
- Extracting the year from each timestamp.
- Counting unique cyclone occurrences per year.
- Creating a bar chart to visualize annual cyclone frequency.

## Detailed Cyclone Analysis
A specific cyclone (ID 35) is analyzed in detail:
- Filtering data for the specific cyclone.
- Visualizing its movement using an interactive plot.
- Analyzing the cyclone's speed over time.

## VaRNN Model for Cyclone Prediction
The project implements a Variational Recurrent Neural Network (VaRNN) for cyclone track prediction:
- Setting up the required environment and dependencies.
- Running the training script for the North Indian Ocean dataset.
- Comparing different model types (RNN, LSTM, Bayes-RNN, Bayes-LSTM) for track and intensity prediction.

## Results Analysis
The results of the model training are analyzed:
- Collecting results from multiple training runs.
- Compiling and displaying summary statistics for intensity and location predictions.

This project provides valuable insights into cyclone behavior and demonstrates the application of machine learning techniques for cyclone prediction, which has significant implications for early warning systems and disaster management.
