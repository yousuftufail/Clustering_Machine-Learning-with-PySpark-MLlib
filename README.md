# Clustering_Machine-Learning-with-PySpark-MLlib

This example is an example of unsupervised learning. RDD construction, conversion to dataframe and visualisation of 16 different clusters can be seen.
This example is taken from DataCamp.


# Import libraries for this implementation

import findspark
findspark.init("path_to_spark-3.1.2-bin-hadoop3.2")


import SparkConf
import SparkContext

sc = SparkContext.getOrCreate(SparkConf())

import SparkSession
spark=SparkSession.builder.getOrCreate()

import KMeans from pyspark.mllib.clustering

import pandas 

import matplotlib.pyplot


