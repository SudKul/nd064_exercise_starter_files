# nd064_exercise_starter_files
This repository contains the files and datasets used in the exercises and the demos in nd064 c1, c2, and capstone. 


## Cloud Lab - AzureMLStudio-3
- AutoML.ipynb: This files is also available in the Udacity public repo [here](https://github.com/udacity/nd00333_AZMLND_Internal/blob/master/C1-use-azure-ml-platform/starter_files/AutoML.ipynb). It is used in the **Cloud Lab - AzureMLStudio-3** lab in C1. 

In this exercise, we'll take the NBA data we used in an earlier exercise and try using AutoML on it. You do need to upload the CSV into the **Data** section. 

- Click on the Data option on the left blade.
- Click on the **+ Create** button.
- Provide a dataset name, say *Nba-dataset*.
- Choose the Dataset type as *Tablular* from ML v1 API, and click Next.
- Choose the **From web files** and provide the dataset file link to use in your ML Studio: 
https://experienceazure.blob.core.windows.net/templates/udacity-nanodegree/nba-2017-players-with-salary-wiki-twitter.csv
- Accept the remaining configuration as default, and finish creating the Dataset. 
