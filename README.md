# Election-Analysis

## Overview of Election Audit
A Colorado Board of Elections employee gave me the following tasks to complete the election audit of a recent local congressional election.

1. total number of votes cast
2. complete list of candidates who received votes
3. percentage of votes each candidate won
4. total number of votes each candidate won
5. the winner of the election based on popular vote

The purpose of the challenge assignment was to calculate the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. To successfully complete this challenge, I used my election_results.csv file and my election_results.txt file as my resources.

## Resources
- Data Source: election_results.csv

## Summary
The analysis of the election show that:

Total Votes: 369,711

The candidates were:

- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

The candidate results were:

- Charles Casper Stockham recieved 23.0% of the vote and 85,213 votes
- Diana DeGette received 73.8% of the vote and 272,892 votes
- Raymon Anthony Doane received 3.1% of the vote and 11,606 votes

The winner of the election was:

- Diana DeGette who recieved 73.8% of the vote with a winning vote count of 272,892 votes.

Number of Votes for each county:

- Jefferson: 10.5% (38,855)
- Denver: 82.8% (306,055)
- Arapahoe: 6.7% (24,801)

The county with the largest number of votes was Denver.

Results can also be seen below:

<img width="310" alt="Screen Shot 2021-08-28 at 3 30 24 PM" src="https://user-images.githubusercontent.com/88108455/131228844-f963559a-bde5-4e69-9aad-1c2b52ff4797.png">


## Election Audit Summary

This script can be used for any election with the following modifications:
- Ensure that your election results can be uploaded into the script as a csv file. The format for another STATE election should be: [Ballot ID, County, Candidate Name]
- If you would like to use this script for a federal election, I recommend switching the "County" column to represent States.
- You can also use this script for smaller elections such as electing a town mayor. You probably could get rid of the county column here since everyone is from the same town. 



