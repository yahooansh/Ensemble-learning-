# Projects
## ETL PROCESS 
Organizations often gain data from multiple sources, filter and clean it and then load the data onto different systems for visualizations and analysis. Over time, many of these systems may become disconnected and not performing optimally. As a Big Data Developer, trying to combine data from multiple sources into one or more other sinks. The go-to technologies for transferring data are often Apache Kafka and Spark Streaming. In this Project i will mimic an ETL process (short for extract, transform and load) using Spark Streaming and different data sources.

For this project, spark streaming will be reading data. The data will then be aggregated and sent to a Kafka sink depending on the type of data that it is. For any data that involves sitting or standing, the data is sent to a Kafka topic called
"idle". For any data other than sitting or standing, the data is sent to a Kafka topic called "active". Two consumers should then read the data and display the activity and time according to the type of activity
