# Election-Analysis

## Overview of Election Audit: 
The purpose of this project is to provide the audit results to the election commission for the recent local congressional election.
The following questions will be answered at the end of this audit.
Calculate the total votes cast
Get a complete list of candidates who received votes
Calculate the total number of votes each candidate received
Calculate the percentage of votes each candidate won
Determine the winner of the election based on popular vote
Calculate the total votes cast in each county
Get a complete list of counties where votes were cast.
Calculate the total number of votes in each county
Calculates the percentages of votes cast in each county
Determine which county had the largest votes

## Election-Audit Results: 
The outcome of election as following:
There are 369,711 total votes cast in the election. 
Below is the breakdown of the number of votes and the percentage of total votes for each county.  
![image](https://user-images.githubusercontent.com/103588178/168516518-78e25f2b-e7a6-4ce3-b1f4-07f092ff299e.png)


The county that received the largest number of votes is Denver with 306,055 votes.
Below is the result of votes and the percentage of total votes that each candidate received for this election.

![image](https://user-images.githubusercontent.com/103588178/168516575-f846987e-4964-40fd-b509-1f2579824cee.png)

The candidates were: Charles Casper Stockham, Diana DeGette, Raymon Anthony Doane.  The winner of this election is Diana Degette who received 73.8% of the votes and 272,892 votes.  

## Election-Audit Summary: 
The script can be used for any elections with the same features (Ballot ID, County, Candidate) in the .csv file.  One way to calculate the local election votes such as the school district board election, we can request the .csv file with local school information.  Then we can simply modify the current codes by changing the county to school: school_votes[school_name] +=1.
Another way we can use the codes to calculate the vote for the national election votes for each state, first we can request the dataset with State information.  Then we can ask the user to input the state information with the code: State = input(“Please enter the state you want to see the total votes?\n”).  Then use the for loop to go through all rows and get the total votes for the input state with the code: state_vote[state_name] +=1. 

## Resources 
Data source: Election_result.csv
Software: Python version 3.7, Visual Studio Code version: 1.67.1
