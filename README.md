# Objective
The project involved in developing a criterion to shortlist the best squad of 25 players based on performance parameters with the help of python libraries including Numpy, Pandas, Matplotlib and Seaborn using Jupyter notebook.
# Data Source
The dataset was taken from Kaggle website in the form of a comma-separated values(csv) file.
# Procedure
The project can be segregated into two broad divisions:
1) Data Cleaning & Transformation
2) Key Performance Indication(KPI) & Data Analysis
# Data Cleaning & Transformation
## Transformation
It was the foremost step of the entire project that involved disecting the entire dataset of 235 records having 16 columns each on the basis of 'Nationality' and 'Player Type'.
The large dataset was thus converted into subsets for better data handling and analysis.
## Cleaning
During the inspection of the data it was observed that there were many null values present in the dataset. So it was really important to handles the missing data carefully.
In case where a particular player's entire performance parameters were missing, that record was simply neglected for this analysis.
Now in case where partial missing data was present for a particular player, the missing values were filled with mean value of that particluar performance parameter.
Before simply filling the missing data with mean values, the outliers were removed in case they were present because outliers influence the mean value in a negative way.
