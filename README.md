# s3-spark-postgresql

A pipeline template written for fellows in Insight Data Engineering Program NY 20A.

You can use it with the tutorial, see the [document](https://docs.google.com/document/d/1Ug7yPnykCLUR_kQN6N1m4wkEFCLoHwE4sKomcKLuP8w/edit?usp=sharing).

### Introduction

This is a pipeline example of loading data from Amazon S3 to Spark and do some simple Dataframe processing, and store the data to PostgreSQL. The use case is word frequency calculation.

### Environment
The current pipeline contains the following EC2 nodes:
* 1 Spark Cluster installed with [Pegasus](https://github.com/InsightDataScience/pegasus) (4 m5.large nodes)
* 1 PostgreSQL Node (1 t2.micro node)
