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
  
После поиска в открытых источниках было принято решение использовать следующий датасет -
  
* [Disease Symptom Prediction](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset)  
   
При беглом осмотре сделаны предварительные выводы:
- датасет годится для проверки гипотезы о возможности предсказания болезни по известным симптомам.
- датасет не новый данных по ковиду возможно нет.
- релевантность датасета неизвестна.   
    
Проведём более глубокий анализ.
- анализ проведён в файле -   
 [анализ и подготовка данных ](https://github.com/Aliaksandr-Borsuk/Creating_my_first_project/blob/main/data_analisis.ipynb)  
 
По результатам анализа сделаны выволы:
- предсказание болезни по симптомам задача решаемая.
- подбор гиперпараметров моделей не требуется, т.к. важные метрики (accuracy и  recall ) достигают максимума с параметрами по дефолту.

Можно приступать к созданию приложения.
* [рождение телеграмм бота](https://github.com/Aliaksandr-Borsuk/Diagnostic_bot)
