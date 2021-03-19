# ETL-Project

Techncial Report:

Data was extracted from two csv files containing rotten tomatoes review data and film data on various streaming platforms respectively. Data was cleaned to remove any unecessary columns and renamed so that variables would match created tables when loaded into the postgres data base. Data was inputted into tables within the postgres data base for easy data manipulation. 

To recreate the ETL process utlized please follow the below steps: 

1. import pandas and engine for sqlalchemy
2. read csv file and store into pandas dataframe
3. review columns of each dataframe
4. remove uncessary columns/ rename to match created tables in postgres
5. create schema in postgres for data to be load into
6. connect jupyter notebook to postgres (enter own password in connection string)
7. use pandas to load csv converted databse into postgres
8. use pandas with engine to confirm data in notebook 


The data for this project was selected to analyze the available films on various popular streaming platforms such as HULU, NETFLIX, and DISNEY+ and see how they were reviewed on the popular critique site Rotten Tomatoes. Using these data sets, there is a potential for more interesting views such as identifying which platform has the most highly rated films in its inventory. Additionally, combining these data sets via a common identifier such as move title may potentially allow for a more hollistic view that can provide users with more indepth information on films available on each streaming platform i.e. genre, actors, directors etc. 

