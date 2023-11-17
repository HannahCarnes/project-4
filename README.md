# project-4

## Project Title:
    Wine Quality
-------------------------------------------------------------------------------

## Team Members:
* Jimmy Cowden
* Manroop Gill
* Chase Scarboro
* Hannah Carnes
* Emily Shewcraft

-------------------------------------------------------------------------------

## Project Description/Outline
### Data Collection and Analyses
1. Imported data found in Kaggle
2. Cleaned and prepared data (ETL) utilizing Pandas in Jupyter Notebook
3. Compared variables to address research questions
4. Utilized SciKit Learn supervised machine learning algorihtms to predict wine quality


### Presentation and Summarization 
5. Created visualizations using matplotlib and Tableau
6. Summary of conclusions and written analysis 

-------------------------------------------------------------------------------

## Research Questions
1. Which factors are most useful for predicting best quality wine?
2. Do higher quality wines tend to be more/less sweet? More/less acidic?
3. Can you use citric acid, sugar, chloride, etc content to predict wine quality?

-------------------------------------------------------------------------------

## Datasets
Wine Quality
(https://www.kaggle.com/datasets/rajyellow46/wine-quality/)

Slidedeck
(https://docs.google.com/presentation/d/1KghxU4Y_OcjtaLSivdDUJ0LY9ekpGSVdr8m-HA9NGGI/edit#slide=id.p)

-------------------------------------------------------------------------------

## Task Delineation
* Jimmy - Research, machine learning, presentation
* Manroop - Research, data analysis, visualizations, presentation
* Chase - Research, data analysis, visualizations, presentation
* Hannah - Research, data analysis, visualizations, presentation
* Emily - Research, project proposal, data cleaning, presentation

-------------------------------------------------------------------------------

## Repository Table of Contents
* "Clean_Data": folder containing ETL/analysis Jupyter Notebook files and cleaned CSVs
* "Resources": folder containing original data files
* "Supervised_learning_Wine_quality_predicting": Jupyter Notebook containing machine learning predictions and analysis

-------------------------------------------------------------------------------

## Analysis
For white wine, we can see that the acidity dips then curves back up as quality increases. We can also see that sugar drops steeply towards the higher end of the quality ratings. Alcohol content increases steadily as quality increases.

For red wine, we can see that the acidity steadily decreases as quality increases. We can also see that sugar stays relatively consistent, then increases towards the higher end of the quality ratings. Alcohol content increases steadily as quality increases.

Using Logistic Regression, we were able to predict "Good" (quality rating of 6 or highter) or "Bad" (quality rating of 5 or lower) at an accuracy rate of 88.2% for red wines and 79.5% for white wines.

-------------------------------------------------------------------------------

### Conclusion
To summarize, we used a supervised learning model to predict the quality of both red and white wines with an accuracy score of 80% or higher. The data used was sourced from Kaggle, and in the form of a CSV file. We also utilized Tableau to create interesting and informational visuals to aid in the representation of our findings. 

This serves as an example for using Machine Learning techniques to make predictions on real world data. Chemical composition of wine can be used to predict quality!

Our data was limited to the scope of red and white variants of the Portuguese “Vinho Verde” wine. In a perfect world, we can expand this analysis to various types of wine, and collect additional data for feature use (Grape type, selling price, manufacturing price, etc.)

Normalization of the quality scale nullified our necessity to use an outlier detection algorithm, in which there were many more wines that were “normal” vs. “excellent” or “poor.

-------------------------------------------------------------------------------
