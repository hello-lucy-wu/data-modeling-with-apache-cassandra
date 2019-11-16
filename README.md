# data-modeling-with-apache-cassandra
This project is to learn data modeling with Apache Cassandra based on log data from my previous project [data-modeling-with-postgres](https://github.com/hello-lucy-wu/data-modeling-with-postgres/tree/master/data/log_data/2018/11). In file `script.ipynb`, I developed three denormalized tables optimized for the following queries:

1. Show the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Show the name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Show user name (first and last) in the music app history who listened to the song 'All Hands Against His Own'
