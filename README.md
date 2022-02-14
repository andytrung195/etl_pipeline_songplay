<<<<<<< HEAD
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



=======
# etl_pipeline_songplay
>>>>>>> origin/main
