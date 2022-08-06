# HackBackpackers_Sachin

Problem Statement 1 - Lineage problem statement

An SQL Statement will be passed to the Python function that trace the complete lineage and produce the originating table for each output column of the input query.

# Description

We are passing the entirre SQL query and find the Inner query first and extracting the Table name along with the ALIAS name from Subquery. For this use case we have considered two SUB Query so extracting the Table name and Aliasing respectively. 
Later on we are also parsing the outer Queryy to extract the column names.
Finally merging the output of Inner Query along with output Query Column name and producing the output

 

# Prerequisite
NA

 

# How to run

<Write steps to run your solution>

Steps

1. pyhton process_sql.py

2. 
 

# Any other points to mention

<Any other points if you want to mention>
