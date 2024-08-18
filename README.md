# NBA Games Analysis
## Overview
This repository contains the analysis and modeling of NBA game data from the 2004 to 2022 seasons. The project explores various statistical methods, including Bayesian Hierarchical Modeling and Generalized Linear Models (GLM), to answer key research questions about NBA teams' performance and player aggressiveness during and after the COVID-19 pandemic.

## Project Structure
- **Data_102_Final_Report.pdf:** This report documents the full analysis, methodology, and conclusions drawn from the NBA dataset. It covers two major research questions:
    1. **Bayesian Hierarchical Modeling:** Investigating whether NBA teams played more aggressively (measured by personal fouls) during the COVID-19 "Bubble" season compared to the post-COVID season.
    2. **GLM/Nonparametric Methods:** Predicting whether the home team will win a game based on average player statistics and team statistics.
- **bayesian_hierarchical_modeling.ipynb:** A Jupyter Notebook implementing Bayesian Hierarchical Modeling to evaluate team aggressiveness during and after the COVID-19 season.
- **glm_nonparametric_methods.ipynb:** A Jupyter Notebook implementing GLM and nonparametric methods to predict game outcomes based on team and player statistics.

## Data Sources
The dataset used in this analysis was sourced from Kaggle, containing NBA game statistics from 2004 to 2022. The dataset includes:
- **games.csv:** Game-level data.
- **games_details.csv:** Player-level game data.
- **teams.csv:** Team details.
- **rankings.csv:** Team rankings over the years.

## Research Questions
1. Bayesian Hierarchical Modeling Question: Did teams play more aggressively during the COVID "Bubble" season compared to the post-COVID season?
  
      This analysis uses Bayesian Hierarchical Modeling to estimate team aggressiveness, defined as the average number of personal fouls per game. The study provides insights into whether the unique conditions of the COVID "Bubble" season affected team behavior.

2. GLM/Nonparametric Methods Question: Given a particular game, will the home team win based on the team’s average player statistics and team statistics?
      
      This question is explored using GLMs and nonparametric methods such as K-Nearest Neighbors (KNN). The analysis helps identify key factors that contribute to a team's success in a game.

## Team Members
Angel Lee

Ansh Gupta

Antoine Lavoie

Nishka Govil

## Key Findings
Bayesian Analysis: The majority of teams displayed higher aggressiveness during the COVID season compared to the post-COVID season, contrary to the initial hypothesis.

GLM/Nonparametric Analysis: The KNN model was found to be the most effective at predicting game outcomes, achieving an accuracy of 68.5%.

The analysis highlights significant trends in NBA game data, particularly in the context of the COVID-19 pandemic. The project underscores the value of combining statistical models to derive insights from complex datasets.
