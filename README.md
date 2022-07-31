# python-Projects:
In this two projects, illestrate the financial records by analyzing bank data, theremore, created a Python script for analyzing financial records and election data.





### Before You Begin
The repository contain two datasets, analysing folder and both includes:
  * A file called `main.py`. This will be the main script to run for each analysis.
  * A "Resources" folder that contains the CSV files.
  * An "analysis" folder that contains text file that has the results from analysis.

1## PyBank

![](Images/revenue-per-lead.png)

*This project analyzing the financial records of bank company, using set of financial data called [budget_data.csv](PyBank/resources/budget_data.csv). The dataset is composed of two columns: `Date` and `Profit/Losses`.

* The programing language that I used is a Python script that analyzes the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

* The analysis looks below:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

* At the end,the summary analys to the terminal and export a text file with the results.

2## PyPoll


* In this project, analize the election datain  a small, rural town and modernize its vote counting process.

* Iused the set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`.
*  create a Python script that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

* The analysis looks below:

  ```text
  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan
  -------------------------
  ```

* The final script should both print the analysis to the terminal and export a text file with the results.

Thank You..


