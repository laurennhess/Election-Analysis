# election-analysis

## Election Audit Overview
### For this analysis, we used the election_results dataset given by the Colorado Election Commitee to find the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. From the results we generated, we were able to determine the projected winner of the local congressional election and the percentage of votes the winning candidate received. 

## Election Audit Results
### Below are the results or our election audit analysis: 

* There were a total of 369,711 votes cast in this election. 

* Votes by County
  County | Number of Votes | Percentage of Votes
	------- | --------------- | -----------
	Jefferson | 38,855 | 10.5%
	Denver | 306,055 | 82.8%
	Arapahoe | 24,801 | 6.7%

* The county with the largest number of votes was Denver with 306,055 votes and a voting percentage of 82.8%.  

* Votes by Candidate
  Candidate | Number of Votes | Percentage of Votes
	------- | --------------- | -----------
	Charles Casper Stockham | 85,213 | 23.0%
	Diana DeGette | 272,892 | 73.8%
	Raymon Anthony Doane | 11,606 | 3.1%

* The candidate that won the election is Diana Degette. 
	Candidate | Winning Vote Count | Winning Percentage
	------- | --------------- | -----------
	Diana DeGette | 272,892 | 73.8%
	
## Election Audit Summary 
### This script can be used to analyze an election csv file and write the results of the election to a separate text file. We can import any data set in the form of a csv into this script and modify any variable names, indexes, etc. to acheive the election results. Additionally, some iterations through any 'for loops' may need to be changed based on the data setup in the csv file. For example, in our data set, candidate names were in row 2 and county name was in row 1, which may be different than the data set you choose to upload. 
