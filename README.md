# IPL_Dataset-Python
Background:
You are provided with 2 fictional dataframes based on Indian Premier League (IPL). The first dataframe contains the data for all the teams who participated in the year 2018. In the second dataframe, the data is for the year 2017.

Data-Dictionary:
Team: Team name
Matches: Total number of matches played
Won: Number of matches won
Lost: Number of matches lost
Tied': Number of matches tied
N/R: Number of matches with no result
NRR: Net run rate (Rate of scoring the runs)
For: Sum of runs scored by the team against other teams
Against: Sum of runs scored by the opposite playing teams

You have to create a new column 'Points' in both the dataframes that stores the total points scored by each team. The following scoring system is used to calculate the points of a team:

Win: 2 points
Loss: 0 points
Tie: 1 point
N/R (no result): 1 point
