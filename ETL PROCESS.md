# Projects
## ETL PROCESS 
Organizations often gain data from multiple sources, filter and clean it and then load the data onto different systems for visualizations and analysis. Over time, many of these systems may become disconnected and not performing optimally. As a Big Data Developer, trying to combine data from multiple sources into one or more other sinks. The go-to technologies for transferring data are often Apache Kafka and Spark Streaming. In this Project i will mimic an ETL process (short for extract, transform and load) using Spark Streaming and different data sources.

For this project, spark streaming will be reading data. The data will then be aggregated and sent to a Kafka sink depending on the type of data that it is. For any data that involves sitting or standing, the data is sent to a Kafka topic called
"idle". For any data other than sitting or standing, the data is sent to a Kafka topic called "active". Two consumers should then read the data and display the activity and time according to the type of activity
 ![1726989384712](https://github.com/user-attachments/assets/e6a7fa7f-5289-4b81-8f37-a8338948ad25)
![1726989433149](https://github.com/user-attachments/assets/a9fcd053-601a-4be4-a2df-578559db162e)
![1726989454644](https://github.com/user-attachments/assets/0a4e75b1-5915-45a7-8d76-baca241a3e61)
![1726989481912](https://github.com/user-attachments/assets/a98a0ff8-19ae-45ad-ac23-66e0a9e31b1f)
![1726989504309](https://github.com/user-attachments/assets/a588710d-2da1-4ac1-ab73-95e87d4b7afd)
![1726989527977](https://github.com/user-attachments/assets/036e21a3-5221-48fe-b2f6-ca6d50e49d70)
![1726989571149](https://github.com/user-attachments/assets/2be20f8c-7597-4f1a-9e26-325a64018a42)
![1726989595137](https://github.com/user-attachments/assets/1193812a-637c-4dab-b910-c814ee592dc0)
![1726989627004](https://github.com/user-attachments/assets/6ca1aa0d-f0be-4285-8632-0a9c63cf3f3d)
![1726989642455](https://github.com/user-attachments/assets/6ecd4e99-6873-4d97-b538-474ece792db5)
![1726989655027](https://github.com/user-attachments/assets/4bf26732-ead2-438a-8df4-cf5dcb7e216b)
![1726989672743](https://github.com/user-attachments/assets/b1513f43-811c-4abf-8648-b1978bea21f6)
