# Election_Analysis

## Project Overview
  In this project we are assisting a Colorado board of election employee in an audit of the tabulated results for the US congressional precinct in Colorado. Our task is to retrieve the total number of votes, a list of the candidates who received votes, the total votes each candidate received, the percentage of votes for each candidate, the total and percentage votes per county, the county with the largest number of votes and which candidate won the election.
  
## Resources
  To accomplish this task we obtained the data from the file election_results.csv and processed the whole data on Python 3.6.1. Then we printed the results of our calculations on a text file.
  
## Election_Audit Results
  After the analysis of the election we found that: 
  * There were 369,711 votes casted on the election.
  * The voting per county was:
    - Jefferson: a total of 38,855 votes which represents 10.5% of the total votes.
    - Denver: a total of 306,055 votes which represents 82.8% of the total votes.
    - Arapahoe: a total of 24,801 votes which represents 6.7% of the total votes.
  * The county with the largest number of votes was Denver.
  * The candidates were: 
    - Charles Casper Stockham.
    - Diana DeGette.
    - Raymon Anthony Doane.
  * The voting results by candidate were:
    - Charles Casper Stockham received 85,213 votes which represents 23.0% of the total votes.
    - Diana DeGette received 272,892 votes which represents 73.8% of the total votes.
    - Raymon Anthony Doane received 11,606 votes which represents 3.1% of the total votes.
  * The winner of the election was Diana DeGette who received 272,892 votes which represents 73.8% of the total votes.
  
  <img width="519" alt="Screen Shot 2020-08-08 at 7 05 16 PM" src="https://user-images.githubusercontent.com/68616522/89722834-7c41fd80-d9bc-11ea-8204-127695f92d93.png">
  
## Election_Audit Summary
  The script that we used to analyze the congressional voting results can be used to analyze an audit state and local elections. For example, for local county elections that would have a winner per county. We could modify the script so for each county we get the candidate, total votes and percentage votes and the winner per county. Also, we could modify the script so it can be used for mayor elections and it would print out the winner, total votes and percentage votes per city. 
  
