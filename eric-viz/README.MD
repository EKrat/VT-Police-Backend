Using data 2010-2015 Vermont State Police traffic stop data from data.vermont.gov.:

1.	I removed all rows where “stop reason” was “external,” like a traffic crash.
2.	I removed all the columns, except “time” and “race.”
3.	I used excel “find and replace” to fit a space between the minutes and “AM/PM.”
4.	I removed all rows where “race” had been left blank.
5.	I placed the time in 24 hour format and sorted the data by hour.
6.	I conducted a count for each hour’s “race” group.