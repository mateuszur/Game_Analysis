# Gamers Preferences Analysis

This repository contains a Jupyter Notebook that analyzes a dataset of Steam games to discover player preferences, the most popular games and genres, sales leaders, and pricing trends.

## Project Overview

The main goals of this project are:
- Identify the most popular games on Steam
- Find out which games and genres have the highest sales
- Analyze the most expensive games and the share of free-to-play titles

The analysis includes:
- Loading and preprocessing a JSON dataset of Steam games
- Cleaning and transforming the data for analysis
- Exploring the structure and key statistics of the data
- Visualizing trends and drawing insights
- Predicting number of released games in upcoming 3 years

## Required Libraries

The following Python libraries are required to run the notebook:
- `pandas`
- `matplotlib`
- `wordcloud`
- `numpy`
- `os`
- `json`
- `collections` (specifically `Counter`)
- `scikit-learn`
- `plotly`

## Installation

To install the required libraries, run:

pip install pandas matplotlib wordcloud numpy scikit-learn

## Dataset

The analysis uses a dataset in JSON format, originally downloaded from Kaggle. The file should be located at:

Analiza_preferencji_graczy/input/games.json

Make sure the dataset is present in the specified path before running the notebook.

To download the dataset, go to this page: https://www.kaggle.com/datasets/fronkongames/steam-games-dataset

## Example Usage

To run the analysis:

1. Clone this repository.
2. Ensure the dataset is in the correct folder.
3. Install the required libraries.
4. Open `gamers_preferences_analysis.ipynb` in Jupyter Notebook or JupyterLab.
5. Run all cells to reproduce the analysis and visualizations.
