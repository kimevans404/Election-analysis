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

Below are screen shots of the Terminal results as well as what was written to the .txt file

<img width="576" alt="Terminal-Snip" src="https://user-images.githubusercontent.com/111471057/190870856-c274aac1-11e2-4c6b-95a7-f767d3202d23.png">

<img width="695" alt="Txt-Snip" src="https://user-images.githubusercontent.com/111471057/190870862-4aef7986-9548-44c1-8492-dd8008523e91.png">


## Election Audit Proposal for Future Projects
With some modification, this script can be used for other elections as well. Currently, the script is running so that it provides specific information regarding county results. The code could be expanded upon to get vote percentage by county for each candidate which can then be used to show county wins. This information would help the candidates should they chose to run again, or help a future candidate running on a similar platform. The code can also be modified to allow the user to chose the voting data to make the current code work for any vote result.
