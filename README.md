# pyspark model implementation
The purpose of this repository is to develop a model example with python and Spark API. The case example uses a kaggle repository https://www.kaggle.com/c/GiveMeSomeCredit. All data for the models are stored on this site (just change variable names without "-" e.g. "NumberOfTime60-89DaysPastDueNotWorse"-> "NumberOfTime6089DaysPastDueNotWorse"). Credit worthiness is predicted in this example. This can be used as a template to setup spark, see how the API can be used for python. The case sample has been developed in a way that most users of python can access this example relatively easy and use it as a reference.

Dependencies: 
Spark 2.1.0 http://spark.apache.org/downloads.html
Scala

Instructions:
if running locally for testing purposes need to add C:\winutils\bin and find winutils.exe (https:
//github.com/steveloughran/winutils) download and save in that location
http://stackoverflow.com/questions/38233228/spark-on-windows-what-exactly-is-winutils-and-why-do-we-need-it

I am using:
anaconda distribution 4.2.0 & python 3.5.2
