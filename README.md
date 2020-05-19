# sparkify_music_app
This is capstone project for Udacity data science nanodegree porgramm. 

no dataset is available in repository because data file is greater than 10GB.
pie charts ploted with plotly cannot be seen in notebook - for that please refer to the blog link 
It uses Spark framework. In order to run on your local machine, you must install Spark and pyspark api.
Use python 3.7 for pyspark - python 3.8 does not work with py spark.

#Following Spark ML libraries are used - 
from pyspark.sql import SparkSession
from pyspark.sql.functions import udf
from pyspark.sql.functions import isnan
from pyspark.sql.functions import to_date
from pyspark.sql.types import DateType
from pyspark.ml import Pipeline
from pyspark.ml.feature import VectorAssembler
from pyspark.ml.feature import StandardScaler 
from pyspark.ml.feature import StringIndexer 
from pyspark.mllib.tree import RandomForest
from pyspark.ml.classification import RandomForestClassifier
from pyspark.ml.tuning import CrossValidator, ParamGridBuilder
from pyspark.mllib.evaluation import BinaryClassificationMetrics
from pyspark.mllib.evaluation import MulticlassMetrics
from pyspark.ml.evaluation import BinaryClassificationEvaluator    
from pyspark.ml.evaluation import MulticlassClassificationEvaluator
from pyspark.ml.classification import LogisticRegression
from pyspark.ml.classification import DecisionTreeClassifier
from pyspark.ml.classification import GBTClassifier
