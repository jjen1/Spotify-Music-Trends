# Spotify 2023 Music Trends 
**Analyzing Top Artists, Tracks, and Albums Using SQL and PostgreSQL**

## Overview

This mini project explores music trends on Spotify in 2023 using a dataset from Kaggle. The primary objective is to identify the **top-performing artists, tracks, and albums**, while practicing core data skills such as data cleaning, relational modeling, and SQL querying.

Through structured exploration and analysis, the project also investigates correlations between track features (e.g., danceability, energy) and their popularity.

## Dataset

The dataset used is sourced from Kaggle: [Spotify Dataset 2023](https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-2023)
- The raw data was cleaned and transformed using Microsoft Excel.
- Cleaned `.csv` files were imported into a **PostgreSQL** database for querying, they're uploaded for convenience.

## Key Deliverables
- **SQL Scripts**:  
  - `sql_queries_1.sql`  
  - `sql_queries_2.sql`  
- **Results Workbook**:  
  - `spotify_results.xlsx` — contains the output of all major queries and visualizations.

## Label Analysis
  - What labels are associated with the most successful albums and singles?
  - Who are the top artists signed to those labels?

- Genre Insights
  - What genres dominate among high-performing tracks?
  - Do specific genres trend more frequently in top charts?

- Track & Album Popularity
  - Which track was the most popular from each album?
  - Is there a correlation between track-level features (e.g., tempo, energy, valence) and:
    - Track popularity?
    - Album popularity?

- Duration & Release Timing
  - What are the average durations of popular tracks and albums?
  - Are there specific release periods (months/seasons) when popular songs are more likely to drop?

## Tech Stack

- **Database**: PostgreSQL  
- **Data Cleaning**: Microsoft Excel  
- **Querying & Analysis**: SQL  
- **Development Environment**: Visual Studio Code (VSCode)  
- **Visualization Tools**: Lucid.co, Excel
