# Module deployment

The goal is to create a logistic regression model that predicts how likely it is an individual to be excessively absent from work.  
After the model is trained, it is exported, together with a custom scaler, which scales only the non-categorical variables.  
The code with the preprocessing of the data, loading the scaler and the trained model are exported as a python module, which is then uplaoded and tested on new data.

## Datasets
The datasets could be downloaded in the repository.

Labeled data for training and testing the model - **Absenteeism-data.csv**  
New unlabeled data - **Absenteeism_new_data.csv**  
The unlabeled data with predicted labels - **Absenteeism_predictions.csv**  

## Python version

Python 3

*Written as the final assignment in the course  [The Data Science Course 2019: Complete Data Science Bootcamp](https://www.udemy.com/the-data-science-course-complete-data-science-bootcamp/)*
