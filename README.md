#Songplay Analysis

##Purpose of this database
This is an song play database for analysis.
There are 5 tables:
###1 Fact Table:
1.**songplays** - records in log data associated with song plays i.e. records with page NextSong
(songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent)

###4 Dimension Table:
2.**users** - users in the app
(user_id, first_name, last_name, gender, level)
3.**songs** - songs in music database
(song_id, title, artist_id, year, duration)
4.**artists** - artists in music database
artist_id, name, location, latitude, longitude
5.**time** - timestamps of records in songplays broken down into specific units
start_time, hour, day, week, month, year, weekday

##How to run
Run **sql_queries.py => create_tables.py => etl.py**

##File structure
1.log_data file: information of all the logging, buying records
2.song_data file: all songs information(title, artist,...)


##Explaination of the files :
1. sql_queries.py   : containing sql queries 
2. create_table.py  : drop table and create table functions
3. etl.ipynb        : developing single file. working with song data and log data , get information and insert into tables 
4. etl.py           : same as etl.ipynb but processing with multiple file
5. test.ipynb       : file to check database