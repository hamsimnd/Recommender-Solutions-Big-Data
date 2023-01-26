# Recommender-Solutions-Big-Data
### By: Merve Nur Özdemir

## Executive Summary

## Table of Content
 * [Brief Description](#Brief_Description)
 * [Languages or Frameworks Used](#languages_or_frameworks_used)
 * [Task 1 - Exploratory Analysis](#exploratory_analysis)
 * [Task 2 - Recommender Design](#recommender_design)
 * [Task 3 - Text Analysis](#text_analysis)
# Brief Description

## Languages or Frameworks Used <a name="languages_or_frameworks_used"></a>
Python: language
PySpark API 
### REQUIREMENTS
---
- **`%%!pip install --trusted-host pypi.org ipython-sql`**
- **`!pip install pyspark`**
> **All of the required modules and libraries are listed below:**
- **for machine learning processes**
```
from pyspark.ml.evaluation import RegressionEvaluator
from pyspark.ml.recommendation import ALS
from pyspark.ml.tuning import TrainValidationSplit, ParamGridBuilder
```
- **for dataframe and spark session processes**
```
from pyspark.sql import SparkSession
from pyspark.sql.functions import * 
from pyspark.sql.types import *
from pyspark.context import SparkContext
from datetime import date, timedelta, datetime
import time
```
### MOVIELENS DATASET INFORMATION
---
The data types that come in the raw file are shown below. Data type conversions were made if necessary.
- **ratings table**
```
userId (INT), movieId (INT), rating (REAL), timestamp (INT)
```
- **tags table**
```
userId (INT), movieId (INT), tag (TEXT), timestamp (NUM)
```
- **movies table**
```
movieId (INT), title (TEXT), year (INT), genres (TEXT)
```
- **links table**
```
movieId (INT), imdbId (TEXT), tmdbId (TEXT)
```


### Task 1 - Exploratory Analysis <a name="exploratory_analysis"></a>
Questions for Task 1 were solved with pyspark.

### Task 2 - Recommender Design: <a name="recommender_design:"></a>
Two methods are used for recommender design. While the first method offers a user-based solution with the ALs algorithm, the second method offers a recommendation on the basis of movies over the KNN algorithm as a comparison.
### Task 3 - Text Analysis: <a name="text_analysis::"></a>
The data was loaded and the code was prepared to create a schema by creating a dataframe over a simple example. In addition, a stopword study was carried out.


## About Me
Hi I am *Merve Nur* 👋 
[You can find professional information about me here.](www.linkedin.com/in/merve-nur-özdemir-738514b0) 
## I worked actively and motivated for 5 years on Data Management, Data Visualization, Analysis on Tables and Financial Analysis in Turkish Red Cresent. 
```
 
