

**Results**

The total number of votes cast was 369,711
The breakdown of votes for each county and the percentage share can been seen in the County Votes section above
The county with the largest number of votes was Denver
The breakdown of votes for each candidate and the percentage share can been seen above
The winner of the election was Diana DeGette with 272,892 votes, or 73.8% of the vote share.

**The analysis of the election show that:**

There were 369,711 votes cast in the election.
The candidates were:
Charles Casper Stockham
Diana DeGette
Raymon Anthony Doane
The candidate results were:
Candidate Charles Casper Stockham received "23.0%" of the vote and 85,213 number of votes.
Candidate Diana DeGette received "73.8%" of the vote and 272,892 number of votes.
Candidate Raymon Anthony Doane received 3.1% of the voite and "11,606" number of votes.
The winner fo the election was:
Candidate Diana DeGette who received 73.8% of the vote and "272,892" of votes.


****Challenge Overview****

This challenge has allowed us to get acquainted to the portion of Python that deals with Data Analysis. A lot to learn and discover. I am more motivated to accumulate more knowledge about Python and other tools.


**challenge summary**

By working with the raw data, presented to us, we have been able to identify  the winner of the election. More importantly, we have uncovered the concentration of the votes. In Denver. One can deduct that any candidate that does well in Denver, 30% or above will never loose the election. 

The script above could immediately benefit the election commission for re-use in future elections. It offers a number of benefits over using Excel / VBA. Primarily, its performance will be much better, especially when used in a larger election with millions of votes. Secondly, the python script can be used, maintained, and improved outside of the data set (for example, by pushing it into GitHub) for use in other elections. This would allow the public to review the code in addition to the results. Some other ways in which the script could be improved:

If the order of the columns are different from election to election, the user could first be prompted to input the column numbers of the relevant headers. For example, the prompt might say

        * Please enter the column number that corresponds to 'County': 2
        * Please enter the column number that corresponds to 'Candidate Name': 3
If multiple .csv files are needed for the analysis, the script could be modified to take in any number of files in the Resources folder, and aggregate the results for all files. This would prevent the user from needing to run the script for every file.
