# Who wants to be a millionaire?

## Prerequisites
You will need all files (millionaire.dos and millionaire.db) for this to work.
You also need the SQLite plugin. This example is known to work with all 2.0 and 
2.1 versions of DialogOS.

## Idea
[Who wants to be a Millionaire?](https://de.wikipedia.org/wiki/Who_Wants_to_Be_a_Millionaire%3F)
is a game in which questions of increasing difficulty need to be answered by selecting an answer
A, B, C or D. This functionality is implemented in this example where the questions are picked 
randomly from a database via SQL.

## Start & Usage
Open millionaire.dos. You'll see some notes on the left and the actual dialog 
specification on the right. Just to make sure, open the settings of the SQLite
plugin (Dialog menu → SQLite-database plugin) and set a correct path to the database
(this is required if the database is not in your working directory). Then, you may
start the dialog. 
