# Election_Analysis

## Overview of Election Audit:

This analysis is to help The election commission with the below requested additional data to complete the audit along with the initial submission of the election audit helping Seth and Tom.

The voter turnout for each county - This calculation determines the total number of votes casted for each county
The percentage of votes from each county out of the total count - This is the percentage of votes casted for each county
The county with the highest turnout - This determins the county that has the highest vote percentage.

## Election-Audit Results:

 * How many votes were cast in this congressional election?
      * Total Votes: 369,711. This is calculated in the output of this analysis written into the analysis.txt file.
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
   * County Votes
       * Jefferson:  10.5% (38,855)
        * Denver:  82.8% (306,055)
       * Arapahoe:  6.7% (24,801)
* Which county had the largest number of votes?
  * The County with largest volume of votes in Denver, with 306,055 total votes making upto 82.8% of the total vote share. This is determined by using an if statement to compare the votes per each county and if the large_county_votes < votes, then we are assigning the votes value to large_county_votes.
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.


| Candidate Name | No. of votes | Vote Percentage |
| --- | --- | ---|
|Charles Casper Stockham | 85,213 | 23.0% |
|Diana DeGette | 272,892 | 73.8% |
|Raymon Anthony Doane | 11,606 | 3.1% |

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    * Diana DeGette won the election with A total number of 272,892, which is making upto 73.8%


## Election-Audit Summary:
This election analysis script could be resued with slight modifications to any elections with any number of geographical localities at any level with any number of candidates contesting. For example: this analysis could be used to calculate and analyse elections where there are multiple candidates contesting from multiple locations and also for a single location with multiple candidates. This script can also be used to calculate the trailing candidate and their vote percentage along with the percent of votes they were trailing by.

          
