# Project introduction

This is a simple project in which three tables have to be created in Apache Cassandra using python and CQL to model the data for 3 different queries.  

# Files

Project_1B_ Project_Template.ipynb is a Jupyter Notebook with : 
1 . all the necessary steps to create a CSV file with the data needed to build the tables and run the querries
2. Create the tables, insert the data in them and run the select statements corresponding to the data required by the project 

# Queries and tables

The following three queries need to have data modelled for them.

1. Return the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4.  
2. Return the name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182.  
3. Return every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'.  

The following three tables were created for this purpose.

1. session_library
2. user_library
3. song_library


