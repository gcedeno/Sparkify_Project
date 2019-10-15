
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Project Components](#components)
4. [Instructions](#instructions)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This Notebook was implemented completely on IBM Watson Studio
running on Python 3.6 with Spark.

Several pyspark libraries are required and listed on the
section `System and Libraries` described in the Notebook.

Additional libraries needed to run the code are the following:   
<ul>
<li>NumPy for numerical vectorize calculations</li>
<li>Pandas for data manipulation</li>
<li>Matplotlib and Seaborn for data visualizations</li>
</ul>


## Project Motivation<a name="motivation"></a>

This Notebook contains the capstone project of the Data Science Nanodegree offered
by Udacity. The goal of the project is to manipulate a large and realistic dataset
using Spark and build a machine learning classifier for predicting churn for the imaginary
music streaming application Sparkify. For all the analysis and model training a Spark
cluster was deployed on the cloud using IBM Watson Studio. This submission corresponds
to the whole project solution from data gathering and cleaning, through exploratory analysis
up to training a Machine Learning Classifier.

Sparkify is an imaginary music streaming application. The idea for this project is
to manipulate a dataset containing user's information using Spark and to engineer relevant
features and learn how to use Spark MLlib to build machine learning models for predicting churn.

Predicting churn rates is a challenging and common problem that data scientists and
analysts regularly encounter in any customer-facing business. Additionally, the ability
to efficiently manipulate large datasets with Spark is one of the highest-demand skills in the field of data.

This project allows to develop two essential data analytics skills, namely:
* Load large datasets into Spark and manipulate them using Spark SQL and Spark Dataframes
* Use the machine learning APIs within Spark ML to build and tune models

## Project Components <a name="components"></a>

**Sprakify_DSND.ipynb** Contains both the code and technical report, it demonstrates the
process of using pyspark to explore the data and build a churn prediction model on IBM Watson Studio.

The main findings of the code can be found at the post available [here](https://medium.com/@gustavo.a.cedeno/sparkify-predicting-churn-with-apache-spark-on-ibm-watson-studio-e6785159c6ae).

## Instructions<a name="instructions"></a>

The analysis was implemented using the dataset "medium_sparkify_event_data.json" provided by Udacity.
To run the code, you need to upload the dataset and Notebook to IBM Watson Studio and modify the starter
code as required to create a Spark session and read in the dataset.  

For instructions on how to use IBM Cloud Services as well as how to perform data analysis and model
deployment on IBM Watson Studio, please refer directly to [IBM Cloud](https://cloud.ibm.com)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to [Insight Data Science](www.insightdatascience.com.) for the data, project idea
and Spark course which was the main resource used for this implementation.

Author: Gustavo Cedeno following recommendations and requirements from Udacity's Data Science Program.
[DSND Capstone]Cloud Deployment Instructions.

This project can be used as a tutorial on how to launch a Spark cluster on IBM Watson Studio,
feel free to use the code as you wish!

# Sparkify_Spark_on_IBM_Watson_Studio
