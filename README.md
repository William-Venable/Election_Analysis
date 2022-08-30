# Election_Analysis

## Project Overiew
A colorado Board of Elections employee has given me the folling tasks to complete the election audit of a recent local congressional election.
  1. Calculate the total number of votes cast.
  2. Get a complete list of candidates who received votes.
  3. Calculate the total number of votes each candidate received.
  4. Calculate the percentage of votes each candidate won.
  5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election shows that:
  - There were 369,711 votes cast in the election.
  - The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
  - The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote which is 85,213 votes
    - Diana DeGette received 73.8% of the vote which is 272,892 votes
    - Raymon Anthony Doane received 3.1% of the vote which is 11,606 votes
  - The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote which is 272,892 votes

## Challenge Overview
Following the challenge assignment, I was given the following tasks to complete following the election audit for the previous PyPoll.
  1. Get a complete list of counties that voted.
  2. Calculate the total number of votes from each county.
  3. Determine which county had the largest vote count.
  
## Challenge Summary
The analysis of the challenge shows that:
  - The county vote results were:
    - Jefferson submitted 10.5% of the total vote count (38,855)
    - Denver submitted 82.8% of the total vote count (306,055)
    - Arapahoe submitted 6.7% of the total vote count (24,801)
  - The county with the largest turnout was:
    - Denver

Full Election Results shown below:

![Election_Results](https://user-images.githubusercontent.com/110737061/187561704-1856d152-e814-4d66-8179-4544b60f6411.png)

The script used for this local election could be also applied to something as big as a presidential election with only a few modifcations to the code such as:
  - Switching counties to US states
  - Implementing a for loop to determine the percentage of Democratic and Republican votes
