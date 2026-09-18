# Projects
This section will document my data science projects, research questions, and data stories I created throughout the semester.
---
## Project 1
Analyzing Data in Soccer - Do goals scored actually equate to wins?

Obviously, if a team scores more goals in a match they will win the game. However, this does not always result in season success. For example, Chelsea scored 6 goals in their match a few weeks ago, which is more than some teams have scored all season. Does this mean they will have more team success? The number of wins will be determined by looking at wins, losses, and ties out of the 38 games they play. Wins will be analyzed by looking at how many games the team wins at the end of the season. The number of goals will be determined by adding together how many goals the team scores each game. These would be found in the stats as "Goals For" or "GF".

Code and Visualizations: https://github.com/oradford/data-science-portfolio/blob/main/projects/DTSC%20Project.ipynb

Results Explained: Looking at the first figure, we can see that the top teams in the league did in fact score the most goals. In the second figure we can see that there is a positive correlation between wins and goals scored. The data ultimately shows that there is a strong positive correlation between the amount of goals a team scores in a season and the amount of games a team wins in a season. In conclusion, we can assume that, if Chelsea continues to be one of the highest scoring teams in the Premier League, they will win a good percentage of their games and be one of the best teams in the league.

Ethics and Limitations: This dataset is limited because of the fact that I could not obtain the API that shows the data for every Premier league team. Additionally, the data from this was recorded in the 2023-2024 season and could just have been that one season's trend. One question that I would explore for this conclusion if I had more time and data is if this is the case for all sports. For example, would a team that scores 30 points per game win more games than a team that only allows 7 points per game?

Underlying Code: https://www.thesportsdb.com/ AI Usage Disclosure: Google Gemini was used in order to help debug sections of the code. Gemini was also used in order to help find the dataset. All functions were manually validated through testing.

References: TheSportsDB (2024). English Premier League 2023–2024 season lookup table. TheSportsDB REST API. https://www.thesportsdb.com/api/v1/json/3/lookuptable.php?l=4328&s=2023-2024 Sports Reference LLC. (2024). 2023–2024 Premier League stats. FBref. https://fbref.com/en/comps/9/2023-2024/2023-2024-Premier-League-Stats?utm_source=chatgpt.com Google. (2026). Gemini. https://gemini.google.com/
