# Creating_my_first_project
  
<i>Read this in other languages:</i> [<b> Russian </b>](README_RU.md)    
   
Creating a telegram bot for predicting a disease based on a set of symptoms.
##  The project is done within the framework of the track: ODS My First Data Project: от идеи к продукту.
    
* [My First Data Project](https://ods.ai/tracks/my_first_data_project)

## The project topic has been selected
* Task No. 5 “Bio1 medicine”
  * Create a service based on public data that helps to assess diseases by symptoms.
## Stages of project creation.  
### Data search.
  
After searching in open sources, it was decided to use the following dataset -
  
* [Disease Symptom Prediction](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset)  
   
At the first examination, preliminary conclusions were made:
- the dataset is suitable for testing the hypothesis about the possibility of predicting the disease by known symptoms.
- the dataset is not new, there may be no data on covid.
- the relevance of the dataset is unknown. 
    
Let's do a deeper analysis.
- the analysis was carried out in the file -  
 [data analysis and preparation](data_analisis.ipynb)  
  
Based on the results of the analysis, conclusions are made:
- predicting the disease by symptoms is a solvable task.
- the selection of hyperparameters of models is not required, because important metrics (accuracy and recall) reach a maximum with default parameters.

You can start creating an application.
* [building a telegram bot](https://github.com/Aliaksandr-Borsuk/Diagnostic_bot)
