# Assignment-5-DATA-1202


#Project Title <br/>
Creating a Function to calculate distribution of Channel type from to 1000 records from youtube_dataset.xlsx dataset. <br/>

#Prerequisites <br/>
import numpy as np: Utilizing numpy python library. <br/>
import pandas as pd: Utilizing pandas python library. <br/>

#Installing <br/>
Install Anaconda navigator software. <br/>
Install Jupyter Notebook in the anaconda navigator. <br/>
Using Jupyter notebook to implement Python code. <br/>

#Running the tests
Reading the youtube_dataset.xlsx. <br/>
Generating a dataframe of the youtube_dataset. <br/>
Generating a filtered dataframe of 1000 records. <br/>

#Deployment <br/>
The youtube_dataset.xlsx datset is used. <br/>
Initially in the code a python function is created which selects the data frame which contains the top 1000 rows using the iloc function in python. <br/>
Multiple rows and columns are selected using the iloc indexer. df.iloc[:1000, :]  selects the first 1000 rows of a data frame with all columns. <br/>
Secondly, using the value_counts function in python, the count of unique rows is obtained according to the channel type in the data frame of 1000 rows. <br/>
Finally, the function that has been created is called. <br/>
Later this was converted into a resultant data frame into a separate CSV file named “filtered.csv”. <br/>
This was done using the python function df.to_csv, which writes the data frames into a CSV file. <br/>
Finally, this was imported into a new CSV file to a new database table i.e., youtube.filtered in MySQL workbench. <br/>
This was further retrieved as all the top 1000 records of our table using SQL select query. <br/>

#Author <br/>
Kaanan Arora <br/>
Milli Malhotra <br/>
Mubashshir Khan <br/>
Samarth Patel <br/>
Smriti Raina <br/>

#License <br/>
Python 3.9 <br/>

#Acknowledgement <br/>
Libraries utilised: <br/>
https://numpy.org/doc/ <br/>
https://pandas.pydata.org/docs/ <br/>
#Installation of anaconda: <br/>
https://www.anaconda.com/products/distribution <br/>
#Code rerference: <br/>
Provided by Professor Omar Al-Trad.

