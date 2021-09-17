# Election_Analysis

## Overview of Election Audit 
This election audit provides an analysis of each candidate and counties results based on votes. The Election Results analysis provides a total vote count and which candidate and county received what portion of that total number of votes. 

## Election Audit Results 

![Election Audit Results](https://user-images.githubusercontent.com/88383836/133825641-0a79c020-5c2a-40ac-899a-daf9e1bad577.PNG)

## Election Audit Summary

![csv rows](https://user-images.githubusercontent.com/88383836/133825666-7104790f-e86c-4eb2-9fe1-4260663d8378.PNG)

This script can be modified to provide election results to any election. The csv file format plays a role in the code that was formed to produce these results. If the csv file is in the same format as the election_results.csv file, then no changes would have to be made to the script. If the file is in a different format, we must ensure the row where the candidate and county are searched are updated into the script. The picture shown above shows the two rows of code that would need to be changed. Currently it states that the candidates can be found in column 3 and counties can be found in column 2. This essentially aligns the script of code to evaluate the proper columns of data from the csv file. Once we align the data from the csv file with our script the code can calculate the rest of the values necessary.
