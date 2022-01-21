# Political Party Rating
## Problem Statement
The goal of this project is to create an algorithm which will predict a persons rating of both the Democratic and Republican party based on their demographics.

## Motivation
The reason behind creating such an algorithm is to aid candidates and their team in planning and budgeting:
1. Helps identify which communities should be targeted for ad placements.
2. Supports tour planners in knowing which areas to include in a candidate's tour.
3. Allows for better budget allocations.
4. A tool to estimate projections for the candidate.

## Data Source
The data used comes from [Civic Leads](https://www.icpsr.umich.edu/web/civicleads/studies/37188/datadocumentation#).

## Approach
The dataset included a lot of variables which were not related to a persons demographics, because of this I used R to create a new dataframe using only the variables relating to demographics and political party rating. 

## Results
After creating two linear regression models using train test split for both the Democratic and Republican party individually the models were not bias however their prediction for rating between 1-100 was off for both models by around 26 points. Because of this I introduced dimensionality reduction and found that this however made the model less accurate with around a 30 point miscalculation.

## Implementation
The results from both of the models were too poor for proper implementation. In order to achieve our motivation purposes/goals we would need a model with higher accuracy.
