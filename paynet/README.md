# Getting Started
1. Create a directory name `sparkdata`
2. To setup Pyspark, we will use `jupyter/all-spark-notebook` image from [here](https://hub.docker.com/r/jupyter/all-spark-notebook)
3. Run `docker run -d -P --name notebook -v /home/user/sparkdata:/sparkdata jupyter/all-spark-notebook:spark-3.5.0` to start code on the notebook with Spark as background server.

# Observation and Insight

1. Top 5 fraud name are - Scott Martin,  Jennifer Scot,   Robert Jam, Susan Garcia, Linda Davis.
2. Gender showed no significant different between Male and Female in terms of fraud activity.

![image](https://github.com/user-attachments/assets/7e0cd448-b8fd-4d14-9a85-927360baffd4)


3. Grocery pos, shopping net and misc net showed the highest category transaction in fraudulent.

  ![image](https://github.com/user-attachments/assets/bde2dc10-4140-4037-957b-f9e9ecd13a65)

4. Hauston, Warren and Naples cities and Pennysilvania, Texas and New York states has the highest amount of fraudulent transaction.
<br>

![image](https://github.com/user-attachments/assets/8db6be6c-2404-447f-b4fb-fd7b43d4e37d)
[Heatmap of fraud activities location]

5. Based on the timeseries graph of 2019, early and end of year showed the highest amount of fraudulent activity which require additional
information such events that might be occur at that time.

![image](https://github.com/user-attachments/assets/9fe14a9d-a93b-4838-88a3-476fde5159e0)

6. While in 2020, the month data is not suffiecient enough to conculde the most amount of fraud activity, however it showed March and May where it was the
highest one.

![image](https://github.com/user-attachments/assets/0de178b9-acaf-438b-a077-2ce7d9937bfe)


7. Drilling down to the fraud behavior, we can see most of the fraud activity took at 10:00 to 3:00 AM.

![image](https://github.com/user-attachments/assets/93b86496-8d2f-4e7d-be67-cac24be64798)
