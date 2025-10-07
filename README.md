# An analysis of Love Island UK, US, and AU Contestants

The `LoveIslandResults.csv` dataset records Love Island contestants, when they entered and left the villa. The data is sourced from the Wikipedia pages for the following seasons, as of October 2025:
- [UK](https://en.wikipedia.org/wiki/Love_Island_(2015_TV_series)#Series_overview) Seasons 1-12
- [US](https://en.wikipedia.org/wiki/List_of_Love_Island_(American_TV_series)_episodes#Season_6_(2024)) Seasons 1-7
- [AU](https://en.wikipedia.org/wiki/Love_Island_Australia#Series_overview) Seasons 1-6

The data

The `data/raw.csv` file is copy and pasted from the Wikipedia page for every season of Love Island for the following countries:

The `data/preprocess.ipynb` file standardizes the format, and creates the final dataset `data/LoveIslandResults.csv`. This 

The `analysis.ipynb` file conducts EDA on the dataset, using duckdb to run basic SQL on the csv.

## Findings

