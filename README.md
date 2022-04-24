# Election_Analysis

## Project Overview
The Colorado Board of Elections has requested an audit of their recent local congressional election results. The following results were requested and included in the audit analysis: the total number of votes, the voting results from each county along with the county with the largest number of votes, the list of candidates who received votes, the total number of votes each candidate received along with the percentage of votes each candidate won, and the determination of the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code

## Election-Audit Resuls
The analysis of the election show that:
- There were 369,711 votes cast in the election.

    ![Image 1](https://user-images.githubusercontent.com/102122063/164992847-2dc2fabe-a60c-4ff7-a033-49197bc6e583.png)

    **Image 1:** *You can see the script that was used to retrieve the total number of votes*

- The number of votes and percentage of total votes for each county in the precint were:
    - Jefferson county had 10.5% of the vote and casted 38,855 votes.
    - Denver county had 82.8% of the vote and casted 306,055 votes
    - Arapahoe had 6.7% of the vote and casted 24,801 votes.
-The county that had the largest number of votes was:
    - Denver county with 82.8% of the vote and 306,055 number of votes.
    
         ![Image 2](https://user-images.githubusercontent.com/102122063/164992867-0a567250-1826-4bc9-94be-a14feb69aa42.png)

         **Image 2:** *You can see the script that was used to retrieve the county with the largest number of votes followed by another script to retrieve the number of votes for each county and the calculation to find the percentage of votes for each county.* 

- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette, who  received 73.8% of the vote and 272,892 number of votes.

         ![Image 3](https://user-images.githubusercontent.com/102122063/164992885-d766b420-cba8-4645-a96c-a687f55a7b5e.png)

         **Image 3:** *You can see the script that was used to retrieve the number of votes for each candidate and the calculation to find the percentage of votes for each candidate. Once this data was retrieved, script was added to find the winner of the election based on the popular vote.*

## Election-Audit Summary
The script created for the Election Audits has proven to be an efficient and helpful tool for auditing election results. Fortunately, it can be modified for any election. For example, for any future election that provides the same data and is saved in a .csv file, this script can be easily modified to load a new file for analysis. Below is the current script for loading files into Python followed by script to save our analysis to a new file:

![Image 4](https://user-images.githubusercontent.com/102122063/165001263-4a57e363-b716-42ae-8fa3-0c82bd22bf86.png)

Once you’ve located your new file, if it is also located in the same “Resources” folder then you can simply replace "election_results.csv" with the new file name. If it is not in the same folder, then “Resources” or the path to your new folder will need to be updated. These changes will also trickle down to where and how you choose to save your analysis. In the current script, the analysis is saved to a text file, and if you wish to save a new file, then the location and name of the file will need to be changed. 

There are some ways we can make this script go further. If you run an election and want to include more data for analysis like the party affiliation of voters, the script can be modified to retrieve how many votes were placed by Democrats or Republicans as well as the percentage of votes that were cast by Democrats or Republicans.

If you were to utilize a similar data set where only the candidate, county, and votes were available, the script can also be modified to dive deeper. For example, the script can be written to analyze the number of votes each candidate received from a specific county as well as the percentage of votes. This modification may highlight the regions where candidates were most popular. 

This script can be easily utilized with only simple modifications to not only look at different data collected, yet also dive deeper into the current data provided. Having this script to build from can streamline data analysis processes for any future election audits. It can also save time, which will allow for the results to be announced quicker. 

