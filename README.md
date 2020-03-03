# Analysis of Fantasy Premier League
---
** 
<br>
### Table of Contents
[TOC]


<br>
### Introduction
This project involves process like Data Engineering (cleaning, formatting, storing, etc), Data Visualization

**Hypothesis/Problem**: Most people playing Fantasy Premier League often select squad based on thier personal favourite or are biased to select the in-form players or hottest teams in the league *(mainly from Big 6)*. Rather than focusing on actualplayer stats and selecting ones who are consistently doing well compared to their lower price (here price: value assigned to each player in FPL) and hence miss out a chance to perform better than most of the players on an average.
<br>

**Solution**: Based on the Hypothesis, in this project we'll be analysing the data at team level as well as on player level to reaveal some trend and insights. Based on these insights and statistical data we figure out the best possible combination of players for the fantasy team. Then we'll select 11 from this 15 player by considering Fixture Difficulty Ratio and Home/Away Game factor

**Goal**: The final goal of our project was to write a **Pyhton** Algorithm which uses the data from our analysis  to make “smart” picks and selects best 15 players with respect to high return on investment and other condition and build the an optimal Fantasy League squad given our limited budget of 100 Million.


<br>

### Terms Used
**Player Return on Investment (ROI)**: Player Fantasy points / Player Fantasy Cost (in other words our total points return per 1 million Fantasy-dollars spent on a player.)

**ICT Index**: The ICT Index is a feature in Fantasy Premier League, offering insight to help guide your strategies and selections. A football statistical index, it has been developed specifically to give a verdict on a player as an FPL asset.   It uses match event data to generate a single score for three key areas – Influence, Creativity and Threat. These figures then combine to create an individual’s ICT Index score.
<br>
### Tools, Installations and Versions

**Python** - [Python 3.7.6](http://https://www.python.org/downloads/release/python-376/ "[Python 3.7.6]")
    - Numpy 1.18.1 
    - Pandas  1.0.1
    - Matplotlib 3.1.3
    - Seaborn 0.9.0
    - Requests 2.22.0
    - Json 2.0.9
[FPL API](https://fantasy.premierleague.com/api/bootstrap-static/ "[FPL API]")

<br>
### Built With
Jupyter : file type (.ipynb)

<br>

### Project Status
  The project has been completed and is predicting a good set of players giving far better results.

  <br>

### Conclusion
   By removing team/player biases and favoritism and focusing on the actual player stats, allowed our Algorithm to get the most return on our investment and beat the average FPL Fantasy player 
   This deep dive into the player data allowed us to realize that hypothesis generated was true that is we were allowing team favoritism and a tendency to buy a lot of the overpriced players to hurt our overall Fantasy League performance.
   
   **Note:** This analysis is for Premier League Season 2018-19 in Game week 10 particularly. But this can be applied further to any season of the league by providing the required dataset.
