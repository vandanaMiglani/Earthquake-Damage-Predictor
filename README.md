# Earthquake-Damage-Predictor

This notebook solves 2 challenging problem statements centered around the Kaggle dataset https://www.kaggle.com/arashnic/earthquake-magnitude-damage-and-impact, about the Gorkha Earthquake in Nepal in 2015. 

## Overview of the dataset

This dataset contains information about the post-disaster impact of the Gorkha earthquake (April 2015) which occurred in Nepal. It compiles detailed information from 2016 (a year after the earthquake occurred) about the post-earthquake impact on households and buildings.

There are two important aspects to the dataset which are driving our analysis - 
1. Tables (csv_building_structure and csv_building_damage_assessment) contain information about the building structure - number of floors, age of the building, type of foundation, type of roof, plan configuration, etc.. and the damage grade, which was caused by the earthquake (This is a categorical variable).

2. Tables (csv_household_demographics, csv_household_earthquake_impact and csv_household_resources) contain information about the household structure - number of members in the household, income of the household and pre and post effects of the earthquake (in terms of whether members of the household had to stop pursuing their education, changes in living standard, changes in resources owned by the household and their post-earthquake residential arrangement). 

## Intent of exploring the dataset

The intent of exploring this dataset is to relate the pre and post conditions pertaining to an earthquake. The dataset provides various tables containing information about the building structures,the damages caused by the earthquake, individual household information as well as an individual’s information who was affected by the earthquake. By having such in-depth information, we intend to find insights which will help in assessing the level of damage that an earthquake can cause to a certain section of people or society or building.

