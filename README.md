# DSCI400_Sp23

# Mental Health in the Technology Industry

In this project, we aim to analyze mental health survey data from technology workers in order to identify patterns and factors that contribute to mental health conditions. Our goal is to create machine learning models that can predict whether respondents currently have a mental health disorder, determine the factors that most affect mental health conditions in tech workers over time, and create a webpage to showcase our findings. We will be analyzing 6 years worth of survey data conducted from 2016 to 2021 by Open Sourcing Mental Illness (OSMI).









## Required Packages

All of the packages and libraries used in the project are documented in the requirements.txt file with the corresponding version.




## Data

The data is stored in CSV files, and each CSV file was downloaded from OSMI's website (https://osmhhelp.org/research.html). Each year between 2016-2021 has a CSV file, resulting in 6 total CSV files. 

## Description of Directory

Below is a description of each of the files and folders in the root directory.

Folders:
- data: Contains each year's survey data in csv files 
- functions: Contains a python file for data cleaning and a python file for vectorizng the cleaned dataframe

Files:
- data_cleaning_functions.py: Contains functions to clean each year's data and combining them into a combined text matrix, a text matrix representing precovid years (2016-2019), and a text matrix representing during covid years (2020-2021).
- data_vectorization_function.py: Contains a function to convert matrix of categorical text responses to numerical responses.
- Data Exploration.ipynb: Contains the code to visualize the distribution of the vectorized features in histograms. Also contains a correlation matrix between all features in the vectorized dataframe.
- MachineLearningModelling.ipynb: Contains the code of various machine learning models run on the vectorized dataframe, where the output variable we are trying to predict is the answer to the question, "Do you currently have a mental health disorder?" (i.e., the feature labeled was 45). Models so far include logistic regression, random forest, and decision tree models.




## Directions on Acquiring and Running the Code

1. Clone the main repository to a local server.
2. Install Python v3.11.0 and the packages in requirements.txt
3. Ensure that you can open and run Python files and Jupyter Notebook files.
4. All of the Jupyter Notebooks (.ipynb files) contained under the root directory (DSCI400_Sp23) are the main files with Python code to open and run.
5. To run the code in the root directory, download the six CSV data sets from the "data" folder
6. After completing steps 1 through 5, you should be able to open the Jupyter Notebook files and run through the code.

## Contact Information
Email: mc115@rice.edu (Milan Chopra), nyl1@rice.edu (Nasha Wanichwecharungruang), ms161@rice.edu (Matthew Su)
