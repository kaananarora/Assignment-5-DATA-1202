# Assignment-5-DATA-1202


#Project Title
#Creating a Function to calculate distribution of Channel type from to 1000 records from youtube_dataset.xlsx dataset.

#Prerequisites
#import numpy as np: Utilizing numpy python library
#import pandas as pd: Utilizing pandas python library

#Installing
#Install Anaconda navigator software.
#Install Jupyter Notebook in the anaconda navigator.
#Using Jupyter notebook to implement Python code.

#Running the tests
#Reading the youtube_dataset.xlsx.
#Generating a dataframe of the youtube_dataset.
#Generating a filtered dataframe of 1000 records.

#Deployment
#The youtube_dataset.xlsx datset is used
#Initially in the code a python function is created which selects the data frame which contains the top 1000 rows using the iloc function in python.
#Multiple rows and columns are selected using the iloc indexer. df.iloc[:1000, :]  selects the first 1000 rows of a data frame with all columns
#Secondly, using the value_counts function in python, the count of unique rows is obtained according to the channel type in the data frame of 1000 rows.
#Finally, the function that has been created is called.
#Later this was converted into a resultant data frame into a separate CSV file named “filtered.csv”.
#This was done using the python function df.to_csv, which writes the data frames into a CSV file.
#Finally, this was imported into a new CSV file to a new database table i.e., youtube.filtered in MySQL workbench.
#This was further retrieved as all the top 1000 records of our table using SQL select query.

#Author
#Kaanan Arora
#Milli Malhotra
#Mubashshir Khan
#Samarth Patel
#Smriti Raina

#License
#Python 3.9

#Acknowledgement
#Libraries utilised:
# https://numpy.org/doc/
# https://pandas.pydata.org/docs/
#Installation of anaconda:
# https://www.anaconda.com/products/distribution
#Code rerference:
#Provided by Professor Omar Al-Trad.

