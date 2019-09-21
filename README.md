# Sparkify: Predicting Churn With Spark for a Music Streaming Company

As you can imagine, this project is all about Churn. And it is also all about Data Science, Machine Learning and Big Data! Specifically, in this project we will be building up together an end to end Data Science project for a Big Data problem: predicting customer churn.

## Files in this repository
- README.md: the present file
- Sparkify.ipynb: the jupyter notebook with all the code, analysis and models
- Sparkify.html: an HTML version of the jupyter notebook

## How to Run This Project
This project was done using the free Lite account provided by IBM which allow us to use a Jupyter Notebook that uses one driver with 1 vCPU and 4 GB RAM, and 2 executors each with 1 vCPU and 4 GB RAM.

## Used Libraries
- pyspark.sql.functions
- pyspark.sql.types
- pyspark.sql.window
- pyspark.ml.Pipeline
- pyspark.ml.classification
- pyspark.ml.evaluation
- pyspark.ml.feature
- pyspark.ml.tuning
- datetime
- pandas
- seaborn
- matplotlib.pyplot

## Results
Two different Machine Learning pipelines were used in this project: one containing a Logistic Regressor classifier and another one containing a Random Forest Classifier. Both pipelines used a Standard Scaler to scale the created features as well as assemblers and indexers that are required by PySpark to run the models.

Results for both models can be seen bellow:

**Logistic Regression**
- Accuracy: 0.8
- F1 Score: 0.7
- Area Under ROC: 0.61



**Random Forest Classifier**
- Accuracy: 0.75
- F1 Score: 0.74

## Acknowledgements
I would like to ackonwledge Udacity for providing materials as part of the Data Scientist Nanodegree and IBM for providing a very usefull free lite version of Watson that allows us to run code with Spark.
