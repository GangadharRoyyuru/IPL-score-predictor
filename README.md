# IPL-score-predictor
Team members - Sai Gowtham Tamminaina, Gangadhar Royyuru, Vishnu Tej, Aaditya Edupuganti

Tried to predict IPL scores using Batting averages of respective teams and pitch average of particular match
First we have collected the match wise data of IPL 2020, and structured each match as follows
  Match no.  team 1       team 2           runs 1         runs 2           stadium                Overs left
 Team 1 - Team that played first innings, runs 1 - First innings scorecard
 Team 2 - Team that played second innings, runs 2 - second innings scorecard
 Stadium - venue of the match, overleft - At which over the team 2 is able to chase the project
 Model approach
 
 Data collection --> Structuring the data --> Using Jupyter notebook start analysing the data --> Caluclate the batting average of each team --> Calculate the pitch    average of each team --> Develop a model which predicts as follows
                                                    runs 1 = a(Batting average of team 1) + b( Bowling average of team 2) +c (Pitch average)
                                                    runs 2 =  c(runs1) + d(Batting average of team 2)+ e(Bowling average of team 1) + f(pitch average)
                                   Bowling average - The average score that the oppenent team hits against a repective team.
 
