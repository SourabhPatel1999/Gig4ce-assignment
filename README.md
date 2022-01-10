# Gig4ce-assignment

The aim was : provided a data set in CSV format, design a basic data 
pipeline.

Steps involved:
● Take data from CSV and populate it in mongo ( NOSQL) server.
● Write a pipeline to pull data from mongo and publish on google sheet.
● Write an observer on google sheet to trigger back to mongo, if the sheet gets updated by 
an external source.
● Every change in destination ( google sheet in this case ), triggers a 
change to the source

Prerequisites:
a. Install python(version >= 3.6 would be suitable).
b. Install pymongo, pandas and json.

