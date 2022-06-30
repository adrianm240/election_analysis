# election_analysis
# Local Congressional Election Audit
## Project Overview
The project purpose is to audit a local congressional election in Colorado. The election commission requested an analysis of the election result data to certify the winner, but also to determine several other factors, such as voter turnout for each county, the percentage of votes from each county out of the total vote, and the county with the highest turnout. The following tasks were completed to achieve the audit:

1. Calculated the total number of votes cast. 
2. Got a complete list of candidates who received votes. 
3. Calculated the total number of votes each candidate received.
4. Calculated the percentage of votes each candidate won. 
5. Determined the winner of the election based on popular vote.

## Election Audit Results 
The analysis of the election audit showed that: 
- There were "369,711" total votes casted in the election. 

- The per county vote results were:
	- Jefferson: 10.5% of the vote and 38,855 number of votes.
	- Denver: 82.8% of the vote and 306,055 number of votes.
	- Arapahoe: 6.7% of the vote and 24,801 number of votes.

- Denver County had the largest number of votes with 306,055.

- The candidate results were:
	- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 
	- Diana DeGette received 73.8% of the vote and 272,892 number of votes.
	- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 

- The winner of the election was:
	- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Future Project Use
The election commision can reuse this script-with modifications-in future elections for audit purposes. One future use example is in a local election within a single county for a position such as mayor. To do so, the existing code would have to be slightly modified to replace the names of the county_options list, county_votes dictionary, and references to 'counties' throughout the code to a name that more accurately reflects the participating localities. The candidate named variables would not be impacted and could be kept as is.

Another example would be in a statewide race in which candidates were running for multiple political positions. In this case, the code would have to be updated to collect and store more than one candidate_options list and candidate_vote dictionary for each political position getting voted on in the election. The winning candidates and counties would have to be updated to reflect which of the positions they were running for. However, the county specific variables and functions would not require modifications since there are no constraints on them in the for loops and could process 100 counties as well as the 3 in the current script.
