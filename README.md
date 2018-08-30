# sentimentAnalysisDSE
A demo using DataStax Enterprise Analytics, Apache Cassandra, Apache Spark, Python, Jupyter Notebooks, Twitter api, pattern, and Sentiment Analysis

Choose between running Demo by loading live Twitter data or loading data from CSV

### Things To Setup with Live Twitter Tweets
------
#### Versions
* Python 2.7
* DSE Analytics 6
* Latest Version of Jupyter
#### Setup Twitter Account
* Create a Twitter Account and get API access: https://developer.twitter.com/en/docs/ads/general/guides/getting-started.html
#### Install and Start DSE
* Install DSE https://docs.datastax.com/en/install/doc/install60/installTOC.html
* Start DSE Analytics Cluster: dse cassandra -k #Must use -k option for Analytics
#### Set Twitter Environment Variables
* Set and Source Twitter enviroment variables in shell you will start Jupyter from
#### Set Path Variables to use DSE Analytics
* Find full path to <>/dse-6.0.1/resources/spark/python/lib/pyspark.zip
* Find full path to <>/dse-6.0.1/resources/spark/python/lib/py4j-0.10.4-src.zip
#### Start Jupyter with DSE Command
* Start Jupyter with DSE to get all environemnt variables: dse exec jupyter notebook
#### Install Python Packages
* !pip install cassandra-driver
* !pip install tweepy 
* !pip install pattern 
* !pip install panadas
* Counter-intuitive don't install pyspark!!

### Things To Setup with CSV File 
------
#### Versions
* Python 2.7
* DSE Analytics 6
* Latest Version of Jupyter
#### Install and Start DSE
* Install DSE https://docs.datastax.com/en/install/doc/install60/installTOC.html
* Start DSE Analytics Cluster: dse cassandra -k #Must use -k option for Analytics
#### Set Path Variables to use DSE Analytics
* Find full path to <>/dse-6.0.1/resources/spark/python/lib/pyspark.zip
* Find full path to <>/dse-6.0.1/resources/spark/python/lib/py4j-0.10.4-src.zip
#### Start Jupyter with DSE Command
* Start Jupyter with DSE to get all environemnt variables: dse exec jupyter notebook
#### Install Python Packages
* !pip install cassandra-driver
* !pip install tweepy
* !pip install pattern
* !pip install panadas
* Counter-intuitive don't install pyspark!!
#### Copy CSV Files
* Copy CSV files to the same path where the notebook is located

