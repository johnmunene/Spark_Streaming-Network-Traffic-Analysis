# Spark_Streaming-Network-Traffic-Analysis
This is a program writen on python code incorporating Kafka abd pyspark streaming.
Using Kafka producer, the program generates random traffic ip address as traffic, and steams it on confluent topic network-traffic.
The pyspark retreives data from the network-traffic , does some analysis and reload data back to consumer as process data.
