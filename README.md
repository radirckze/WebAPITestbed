# WebAPITestbed

My testbed for testing a hybrid DB design for a real project. 

Using an IoT example to testing - air quality measurements. 
Monitoring equipment information stored in MySQL. Sensor data is stored in Mongo.
Get data from https://www.epa.gov/outdoor-air-quality-data/download-daily-data

Will be testing the following:

1. Using both SQL and NoSQL in same project where the data is correlated.
2. Scalability. Push the sensor data to Mongo so SQL DB is small
4. Experiment with doing analysis on data in Mongo.
3. Using a cache for SQL data. (may not really need to do this.) 

Project details: Visual Studio Code, ASP.NET / C# Core. MySQL and Mongo. 

Note: This is just a testbed where I experiment with stuff so view at your own risk. I may clean it so it can be used as as example at some point.

TBDs:

1. Need figure out whether the SQL id is stored in MongoDB, vice-versa. This depends on how the data will be accessed so probably some SQL id will be stored in MongoDB. 
