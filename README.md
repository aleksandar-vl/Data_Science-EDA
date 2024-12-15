# International Energy Efficiency Trends for the period 1990 - 2014

## Overview
This project aims to analyze international greenhouse gas emissions and energy efficiency trends from 1990 to 2014. The analysis focuses on GDP, population, GHG emissions, and energy consumption to identify the most energy-efficient countries.

## Introduction
This project explores the relationship between GDP, population, GHG emissions, and energy consumption. The goal is to identify the most energy-efficient countries and understand the trends in energy efficiency and greenhouse gas emissions.

## Load the Data
The data is sourced from various international databases. The following datasets are used:
- `GDP_countries.csv`: Contains GDP per capita data from the United Nations.
- `population_countries.csv`: Contains population data from the United Nations.
- `historical_emissions.csv`: Contains greenhouse gas emissions data from Climatewatch.org.
- `all_energy_statistics.csv`: Contains international energy statistics from Kaggle.
- `supply_of_energy.csv`: Contains energy production, trade, and consumption data from the United Nations.

## Data Preprocessing
The data preprocessing steps include:
- Renaming columns for consistency.
- Handling missing values and irrelevant data.
- Converting data types for analysis.
- Merging datasets to create a comprehensive dataset for analysis.

## Exploratory Data Analysis (EDA)
The EDA section includes:
- Checking the shape and data types of the datasets.
- Describing the datasets to identify any necessary corrections.
- Visualizing trends in GDP, population, GHG emissions, and energy consumption.
- Analyzing correlations between different variables.

## Conclusion
The analysis reveals that GDP growth has a strong positive correlation with greenhouse gas emissions and energy consumption. The most energy-efficient and economically well-off countries are the Nordics and France. These countries should be looked to as examples for increasing well-being in terms of climate and energy sustainability and economic growth.

## References
1. GDP per capita at current prices in USD from UN: [UN Statistics](https://unstats.un.org/unsd/snaama/Basic)
2. Population data from the same link above.
3. All greenhouse gas data from Climatewatch.org: [Climatewatch Data](https://www.climatewatchdata.org/data-explorer/historical-emissions?historical-emissions-data-sources=42&historical-emissions-end_year=2014&historical-emissions-gases=177&historical-emissions-regions=All%20Selected%2CWORLD&historical-emissions-sectors=509&historical-emissions-start_year=1990&page=1)
4. International Energy Statistics from Kaggle: [Kaggle Dataset](https://www.kaggle.com/unitednations/international-energy-statistics)
5. Energy production, trade, and consumption of UN: [UN Data](http://data.un.org/)
6. A multi-factor efficiency perspective to the relationships among world GDP, energy consumption, and carbon dioxide emissions: [ScienceDirect Article](https://www.sciencedirect.com/science/article/pii/S0040162505001861)
7. Monitoring changes in economy-wide energy efficiency: From energy–GDP ratio to composite efficiency index: [ScienceDirect Article](https://www.sciencedirect.com/science/article/pii/S0301421505003125#!)

## How to Run
1. Clone the repository.
2. Install the required packages from `requirements.txt`.
3. Run the Jupyter notebook in the folder where the notebook is located.

**Note**: The packages in the `requirements.txt` file are as per the stable version at the time of writing the original project. You may need to update the packages based on the latest versions, which might affect the code.
