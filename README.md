# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. The total number of votes cast
2. A complete lists of candidates who received votes
3. The porcentage of votes each candidate won
4. The total number of votes each candidate won 
5. The winner of the election based on popular vote.

## Resources
- Data source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.68.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The canditates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes.

## Challenge Overview
To complete the audit, the election commission has requested the following additional data:
1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Challenge Summary
After analyzing the results by county:
- The voter turnout for each county:
  - Jefferson had a turnout of 38,855 votes
  - Denver had a turnout of 306.055 votes
  - Arapahoe had a turnout of 24,801 votes
- The percentage of votes from each county out of the total count:
  - Jefferson had 10.5% of the votes
  - Denver had 82.8% of the votes
  - Arapahoe has 6.7% of the votes
- The County with the largest turnout:
  - Denver with a turnout of 306.055 votes and 82.8% of the votes

## Election Audit Summary
The script used to obtain these result can be easily used to anaylize data from other elections. It is perfect to count the amount of votes a candidate would have and the total percentage of votes all candidates had over the overall vote count. It is also great to determine what the turnout voting can be for each one of the counties involved. Depending on the election results data table that is provided, the script can be tweeked to search the correct columns to obtain each candidate and the number of votes this candidate would have. If the given data also includes more information besides the ballot ID and county, the script can be modified to gather this new data and see how it can relate to each one of the candidates.
