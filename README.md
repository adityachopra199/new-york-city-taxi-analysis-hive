# new-york-city-taxi-analysis-hive

### Problem Statement
The New York City Taxi & Limousine Commission (TLC) has provided a dataset of trips made by the taxis in the New York City. The detailed trip-level data is more than just a vast list of taxi pickup and drop off coordinates.  

The records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations (location coordinates of the starting and ending points), trip distances, itemized fares, rate types, payment types, driver-reported passenger counts etc. The data used was collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

This dataset was created by aggregating the aforementioned records. It provides precise location coordinates for where the trip started and ended, timestamps for when the trip started and ended, plus a few other variables including fare amount, payment method, and distance travelled.
![image](fi_about_photo_trip_records.png)

The purpose of this dataset is to get a better understanding of the taxi system so that the city of New York can improve the efficiency of in-city commutes. Several exploratory questions can be asked about the travelling experience for passengers.

In this assignment, we ONLY consider the data of yellow taxis for November and December of the year 2017.

While performing this analysis, you will inevitably make several assumptions. As long as you state these assumptions, you will be awarded marks.

A few pointers before you start the assignment:
- While creating the tables, it is mandatory to define the integers as int and floating points as double. Certain results may be affected if this is not followed and in that case, marks will not be awarded.
- The solution file must contain all the necessary commands to set up the environment before you start querying. These are covered during the course - they involve adding a JAR file and setting parameters of Hive for partitioning. If these commands are not present in your solution file, marks will be deducted
- Lastly, your code should be syntactically correct, concise and commented. Marks are reserved for the comments present along with every question mentioned in the problem statement - make sure you write these comments as you go along writing your queries.
