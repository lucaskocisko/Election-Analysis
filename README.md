# Election-Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to copmlete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visula Studio Code, 1.38.1

## Summary
The Analysis of the election show that:
- There were "x" votes cast in the election.
- The candidates were:
  - Candidate 1
  - Candidate 2
  - Candidate 3
 - The candidate results were:
  - Candidate 1 receved "x%" of the vote and "y" number of votes.
  - Candidate 2 receved "x%" of the vote and "y" number of votes.
  - Candidate 3 receved "x%" of the vote and "y" number of votes.
 - The winner of the election was:
 - Candidate (1, 2, or 3), who received "x%" of the vote and "y" number of votes.
 
 ## Challenge Overview
 ### Overview of Election Audit
The purpose of this election audit is to gather the following information:
- the voter turnout for each county
- the percentage of votes from each couty out of the total count
- the county with the highest turnout
- existing code already found similar info for candidates;(ln 6-10)

![](https://github.com/lucaskocisko/Election-Analysis/blob/main/countyiteration.png)

![](https://github.com/lucaskocisko/Election-Analysis/blob/main/candidateiteration.png)

Using list & dictionaries, variables & tickers, for loops,and decision & repetition statements I wrote code that sources data from a .csv file and writes a .txt file as output.
 
 ## Challenge Summary
 ### Election-Audit Results
 
![](https://github.com/lucaskocisko/Election-Analysis/blob/main/output.png)

#### Results
* total votes = 369711
* Jefferson co. w/ 38855 votes @ 10.%   Denver co. w/ 306055 votes @ 82.8%  Arapahoe co. w/ 24801 @ 6.7%
* Denver is the largest county
* Charles C. Stockham w/ 85213 votes @ 23%  Diana DeGette w/ 272892 votes @ 73.8%   Raymon A. Doane: w/ 11606 votes @ 3.1%
* Diana DeGette won the election w/ 272892 votes @ 73.8% of vote

### Election-Audit Summary
Visual Studio Code and Python offer different ways to look at a dataset. This script is good at showing the breakdown of votes cast in this congressional district. Somes ways to make this code more modular would be to accept a more generic input. If this script was written to take a different reference file, a different election could utilize it. You could also further refine the data by tracking more information like assigning a party to each candidate and seeing how partisanism effects vote count.
