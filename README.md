# FinalProject

## Introduction
This project aims at analysing the performances of the football clubs in the English Premier League for the 2018-19 season. I aim to see how different clubs perform in different stages of the season, how many cards they earn, how they fare against their fellow neighbours. In particular, I will focus on top 6 clubs and see how they fare amongst the other top 6 clubs. This analysis should provide a good insight to football fans around the world on how their club is performing.

## DATA
The data for this project was obtained from this website: https://www.football-data.co.uk/data.php
The dataset consists of the following attributes:

|Column|
|------| 
|Div    
|Date  
|HomeTeam
|AwayTeam
|FTHG
|FTAG
|FTR
|HTHG
|HTAG
|HTR
|Referee
|HS
|AS
|HST
|AST
|HF
|AF
|HC
|AC
|HY
|AY
|HR
|AR
|B365H
|B365D
|B365A
|BWH
|BWD
|BWA
|IWH
|IWD
|IWA
|PSH
|PSD
|PSA
|WHH
|WHD
|WHA
|VCH
|VCD
|VCA
|Bb1X2
|BbMxH
|BbAvH
|BbMxD
|BbAvD
|BbMxA
|BbAvA
|BbOU
|BbMx>2.5
|BbAv>2.5
|BbMx<2.5
|BbAv<2.5
|BbAH
|BbAHh
|BbMxAHH
|BbAvAHH
|BbMxAHA
|BbAvAHA
|PSCH
|PSCD
|PSCA

We use only the first 23 columns for our analysis. The remaining columns are discarded for now.
The decsription of each column is provided here: https://www.football-data.co.uk/notes.txt

## LICENSES OF THE DATASET
The licenses of the dataset are not mentioned under any 'License' page or term on the dataset webpage, but explitcitly mentioned as:
*"You are free experiment with the data yourselves"* and *"Like all of Football-Data's files, it free to download."*
It can be found on this page: https://www.football-data.co.uk/englandm.php

## STUDY
For the various questions mentioned in the Jupyter notebook, I used the csv file provided in this repo. The analysis is focused on the the top6 clubs in the league and 1-2 questions about the league in general. I have tried to analyse how the top6 clubs match up against each other, when compared to the lower ranked teams in England. The three plots that are embedded in this repo are generated to show how the performances of clubs changed in the league through out the season. I also filtered on the dates column in the csv, to see the performance of clubs in the famous 'festive season' of the Premier League, which is notorious to cause injuries to players of different clubs.

## FILES EMBEDDED:
1. CardsDistribution.jpeg: Shows the distribution of cards earned across teams in the league.
2. MonthlySeason.jpeg: Shows teams' positions on a monthly basis.
3. OverallSeason.jpeg: Shows the teams' progression throughout the season by adding the results with each passing month.

## FINDINGS:
We found that
1. The higher a team finishes in the league table, lower is the number of cards earned.
2. Clubs like Arsenal and Chelsea fared decently against the rest of the top 6 clubs, but clubs like Man United and Tottenham were extremely poor.
3. We see that clubs like Liverpool and Man Ciry hardly changed their positions through out the season, where as clubs like Brighton and Wolves showed erratic changes in their performances.
4. Wolves showed a great points tally against the top 6 clubs.

LINK TO THE COURSE: https://wiki.communitydata.science/Human_Centered_Data_Science_(Fall_2019)
