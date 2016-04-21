Project Introduction. 

This project is intended to create an "Active prediction model", through analyzing the duel networks of 
user behavior and information correlation, with Twitter API as current data source.

Project Ultra is intended to have at least three phases. Phase 1 would be data collection, data cleaning, 
data filtering and data storage.

Phase 2 would be some preliminary analysis, classification of information and users, and most importantly, 
sentimental analysis. 

Phase 3 would build on top of Phase 2, with additional insights borrowed from "relevant" mathematical 
disciplines, to create a prediction model, which would not only make predictions with past observations, 
but also make predictions about outcomes of inputs that one might be able to "insert" into the system, 
should one is expecting some desired results from the system itself.

This upload is Phase 1 of Project Ultra. This is the 4th rewrite, as well as the 1st version which could 
analyze data at a speed that is at least 10 times faster that real world time speed.

####################################################################################################

This Project is written with:

1. Python 2.7
2. with standard libraries: JSON, Numpy, Pandas
3. with pymysql for interfacing with MySQL
4. require MySQL

Before executing the programs, please:

1. create your own data base at MySQL, setup user name and password
2. specify those variables at Phase1_Main.py
3. you could reassign new keywords of your own choice
4. it is recommended to collect a bigger data file, at least more than 1 hour real-world-time
5. you should update the data file name in Phase1_Main.py, and place your data file under ./Data

When executing the programs:

1. you could either execute Phase1_Main.py
2. or you could use Phase1.sh

Both under folder ./src

Performance test:
23 hours' real world data, ~ 2 million tweets, finished analyzing in ~3300 seconds, ~ 11,000 related tweets stored.
At anytime, program is tracking ~ 3000 tags and ~ 2500 users respectively.
