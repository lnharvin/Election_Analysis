# Election_Analysis

## Project Overview
A Board of Elections employee has been given the task to complete an audit on a recent local congressional election. Task requirements are as follows:
  1. Calculate the total number of votes cast.
  2. Get a complete list of candidates who received votes.
  3. Calculate the total number of votes received for each candidate.
  4. Calculate the percentage of votes each candidate won.
  5. Determine the winner of the election based on the popular vote.
  6. Calculate voter turnout for each county.
  7. Calculate the percentage of votes from each county out of the total count.
  8. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.1

## Summary
The analysis of the election data show that:
- A total of 369,711 votes were cast
- The county with the largest votes was Denver with 306,055 (82.8%) votes cast.
- The candidates were:

    1 - Diana DeGette
    
    2 - Raymon Anthony Doane
    
    3 - Charles Casper Stockham
    
- The results for each candidate are as follows:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
    - Candidate Diane DeGette who received 73.8% (272,892) of the vote count.

## Challenge Overview
This was a great introduction into Python, I've done some python coding before but I enjoyed this lesson. I wasn't quite able to get my command code output to match the challenge example exactly with the line spacing. If I changed the code to not include the line feed at the end of the results (line 107) then the results would print in a single line in the text analysis file; only for the county votes. 

## Challenge Summary
This program could be reused in calculating the next terms results, provided the format (columns) in the source file are the same which would save time for the next analysist. No additional changes would be needed if new counties were added to the results either.

![Command Line Results](https://github.com/lnharvin/Election_Analysis/blob/main/command_line_election_results.png)
