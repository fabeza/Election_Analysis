# Election Analysis

## Project Overview
A Colorado Board of Elections (CBE) employee asked us to help with the election audit of the State’s 2022 local congressional election by completing the following tasks:

Calculate the total number of votes cast. 
2. Calculate the voter turnout for each county.
3. Calculate the percentage of votes from each county out of the total count.
4. Determine the county with the highest turnout.
5. Get a complete list of candidates who received votes. 
6. Calculate the total number of votes each candidate received. 
7. Calculate the percentage of votes each candidate won. 
8. Determine the winner of the election based on popular vote. 

## Resources
For the election analysis and audit, we used the following resources:
- Data Source: [election_results.csv](https://github.com/fabeza/Election_Analysis/blob/031244a5f78c7d27caffb6501f5ebc62801f1ad8/Resources/election_results.csv)
- Software: Python 3.9.12, Visual Studio Code 1.71.2

## Summary
We are pleased to share the results of the analysis and audit of the 2022 congressional election:

- There were **369,711** total number of votes cast in the congressional election.
- The voter turnout by county was:
  - Jefferson had **10.5%** of the total vote and **38,855** number of votes.
  - Denver had **82.8%** of the total vote and **306,055** number of votes.
  - Arapahoe had **6.7%** of the total vote and **24,801** number of votes.
- The county with the largest number of votes was **Denver** with **306,055** votes.
- There three running candidates were:
  - **Charles Casper Stockham**
  - **Diana DeGette**
  - **Raymon Anthony Doane**
- The candidate results were:
  - Charles Casper Stockham received **23.0%** of the vote and **85,213** number of votes.
  - Diana DeGette received **73.8%** of the vote and **272,892** number of votes.
  - Raymon Anthony Doane received **3.1%** of the vote and **11,606** number of votes.
- The winner of the election was:
  - **Diana DeGette**, who received **73.8%** of the vote and **272,892** number of votes.

The chart below summarizes these findings:

![Election_Analysis_Chart](https://github.com/fabeza/Election_Analysis/blob/bb8876ce07b38df00b582f9e9fb60e4f45d99981/Resources/Election_Analysis_Chart.png)

## Election-Audit Summary
The script we developed for this audit allowed us to efficiently analyze a large data set of over 350,000 votes. Our team of experts developed a highly customizable script that can be adapted to any election. As seen in image #1 below, we can add any data source to the script and it will allow us to read and analyze any election results. Additionally, we can output our results in any desired written form, for this analysis, we used a _.txt_ file.

Image #1

![image_1](https://github.com/fabeza/Election_Analysis/blob/bb8876ce07b38df00b582f9e9fb60e4f45d99981/Resources/image_1.png)

Image #2 shows that the original script was designed to pull the specific audit information requested by the CBE: candidate-specific audit. However, the CBE needed to extend the audit results to also include county-specific information, so we swiftly changed the script to fulfill this request (image #3). 

Image #2

![image_2](https://github.com/fabeza/Election_Analysis/blob/bb8876ce07b38df00b582f9e9fb60e4f45d99981/Resources/image_2.png)

Image #3

![image_3](https://github.com/fabeza/Election_Analysis/blob/bb8876ce07b38df00b582f9e9fb60e4f45d99981/Resources/image_3.png)

This demonstrates how our script can be easily adapted, it can manage larger data sources that involve any  number of votes, candidates, counties, cities, and even states. Wether it’s the Colorado primary elections, municipal elections, or any US general elections, our sophisticated script can be customized to cater to your needs and goals.
