# Election-Analysis

## Overview of Election Audit

The purpose of this project is to conduct an election audit for the Colorado Board of Elections.

The outcome of the congressional election audit will determine the following:

1. Total number of votes cast
2. A complete list of candidates who received votes
3. Total number of votes each candidate received
4. Percentage of votes each candidate won
5. The winner of the election based on popular vote
6. The voter turnout for each county
7. The percentage of votes from each county out of the total count
8. The county with the highest turnout

## Tools Utilized to Complete Analysis
The [Election Results Dataset](https://github.com/cmmgw/Election_Analysis/tree/main/Resources), in a CSV file format, was analyzed by running Python scripts in Visual Studio Code.

## Election Audit Results
The results of the election audit analysis indicate the following:

Total Number of Votes Cast in the Election 369,711
Candidates::
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

Detailed Results of Votes Candidate Received
- Charles Casper Stockham received 85,213 votes, which equates to 23.0% of votes won
- Diana DeGette received 272,892 received votes, which equates to 73.8% of votes won
- Raymon Anthony Doane received 11,606 votes, which equates to 3.1% of votes won

Winner of the Election Based on Popular Vote: Diana DeGette

Detailed Results of Voter Turnout by County:
* Jefferson County had 38,855 voters and 10.5% of votes from each county out of the total count
* Denver County had 306,055 voters and 82.8% of votes from each county out of the total count
* Arapahoe County had 24,801 voters and 6.7% of votes from each county out of the total count

County with the Highest Voter Turnout: Denver County

![election_analysis](https://user-images.githubusercontent.com/105829106/173484544-bd7d9bb3-c2f6-4cc8-90d6-ec3250da2f6a.PNG)

## Election Audit Summary
The script utilized to conduct this analysis can be modified to satisfy future analyses on elections. For example, the script can be modified to handle a larger scale election by simply changing counties to states. Additionally, you can also add congessional dictricts for elections at the federal level.
