# Using K-Means Clustering to Design the Best Teams of WNBA Players of All Time
## (And simulating a data-driven game between the top two teams)

![image](https://cdn-images-1.medium.com/max/2400/1*aXggnBMsODmD-lheAuNT4w.png)

## Overview
Using K-Means Clustering, I ranked all WNBA players into teams based on how well they performed compared to other players in their position. 

## Process
First, I scraped all WNBA player stats from Basketball-Reference.com. I decided the best way to create ranked teams among all WNBA players was to divide all players by position, then cluster players within each position according to that position's best performance metrics, and then combine top ranking clusters into teams. I used K-Means Clustering where k = 8, therefore I created a total of eight teams. At the end of my notebook, I simulate a data-driven game between the top two teams. 

## Conclusion
I was pleased with results of my modeling process. Players were ranked according to how well they performed in multiple categories. Additionally, the number of games played was not a feature used to rank the players. Therefore, the players were ranked by their overall game strategy. After doing this project, I hope to continue exploring data from other womens sports.  
