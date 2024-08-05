# Project Name
2 Top 12 Tight Ends on the Same Team

#### -- Project Status: Active

## Project Intro/Objective
The purpose of this project is to do an EDA on a fantasy football dataset spanning over ten years. Premise we are looking into is the likelihood of 2 Tight Ends from the same team can finish Top 12 in fantasy football. The scoring used is PPR scoring and the ranking of the players is based on season total not points per game. The idea of this EDA came from the NFL reports that the Baltimore Ravens where going to use their 2nd string TE (I.Likely) more in the offense this year. The Ravens already have a top 5 ranked TE on their offense in M. Andrews so I wanted to research if Likely could be a sleeper in a way and what is the possibility of that happening. (Describe the main goals of the project and potential civic impact. Limit to a short paragraph, 3-6 Sentences)

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Pandas, jupyter
* Seaborn
* nfl-data-py 

## Project Description
For this project, I decided to take the last ten years of fantasy football data for TEs. For fantasy football leagues, usually are based on 12 team PPR scoring with one TE slot. So we will be looking at the top 12 ranked TEs for the past ten years. For the data source, retired players have their teams marked as FA, which we have to replace with their actual team for that specific season. Questions for this project are how often has two TEs from the same team have been Top 12 in PPR scoring, what stats were needed for both players to produce (target share, touchdown share,etc), and how big of a jump does I. Likely need to make to become a Top 12 TE in 2024. 
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting

## Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    |   |
    │   ├── deployment           <- Scripts to deploy ml model and make predictations
    │   │   └── deployment.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    └── 


## Contact 
* Feel free to contact with any questions or if you are interested in contributing - https://www.linkedin.com/in/juvarne-hinson/
