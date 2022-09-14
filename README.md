# Election Analysis Challenge

## Overview of Election Audit
A Colorado Board of Education employee assigned the following tasks to audit a recent local congressional election.

1. Calculate the total number of votes cast.
2. Compile a list of participating counties and their individual voter turnout.
4. Find the county with the highest voter turnout.
5. Get a complete list of candidates who received votes and the percentage of votes each candidate won.
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: Election_results.csv
- Software: Python 3.10.6, Visual Studio Code, 1.71.0

## Election Audit Results <!--  Use images or examples of your code as support where necessary. -->
The analysis of the election show that:
- There were 369,711 votes cast in this congressional election.
- The voter turnout was:
    - Jefferson County with 38,855 voters which was 10.5 % of the total votes.
    - Arapahoe County with 24,801 voters which was 6.7% of the votes.
    - Denver County had the largest turnout with 306,055 voters which was 82.8% of the vote.
- The candidates and their results were:
    - Charles Casper Stockham who received 23.0% of the vote with 85,213 votes.
    - Diana DeGette whoreceived 73.8% of the vote with 272,892 votes.
    - Raymon Anthony Doane who received 3.1% of the vote with 11,606 votes.
- The winner of the election was:
    - Diana DeGette with 272,892 votes which was 73.8% of the vote.

## Election Audit Summary
<!-- In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections. -->
With some modification, this script can be used for other elections as well. Currently, the script is running so that a specific file with election data is pulled, but it can be adjusted to request the name of the data file from the user wishing to analyze election data.
