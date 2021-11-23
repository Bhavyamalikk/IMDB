# IMDB
### DESCRIPTION:
The IMDB dataset consists of two comma separated files (.csv) namely - movies & directors.
The movies dataset consists of the names of the movies, release date, revenue, popularity etc. and the directors dataset consists of the names of the directors, their department and gender. 


### TASK:
The task is to query the IMDB Dataset using SQL queries and try to analyse the data using SQL.


### WORKFLOW:
1. You need to establish a connection to the sqlite database by creating a connection.
2. Then, you have to create a cursor using the cursor() method.
3. Then, execute the query -> cursor_object.execute('query')
4. To fetch the data, then use fetchall() method for the cursor object.
