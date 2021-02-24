# Melbourne-pedestrain-count-prediction
Predict pedestrian count based on the pervious sensor data.

Data prodcuer: Apache Kafka producer to simulate the real-time data transfer.

Spark Streaming: Implement Spark Structured Streaming to consumer data from Data producer.Then use given pipeline to predict pedestrain count and create another Kafka producer to transfer result.

Data consumer: Implement an Kafka consumer to consume the data from Spark Streaming and display the sensor location on a map.
