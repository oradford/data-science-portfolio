# Projects
This section will document my data science projects, research questions, and data stories I created throughout the semester.
---
## Project 1
Analyzing Data in Soccer - Do goals scored actually equate to wins?

Obviously, if a team scores more goals in a match they will win the game. However, this does not always result in season success. For example, Chelsea scored 6 goals in their match a few weeks ago, which is more than some teams have scored all season. Does this mean they will have more team success? The number of wins will be determined by looking at wins, losses, and ties out of the 38 games they play. Wins will be analyzed by looking at how many games the team wins at the end of the season. The number of goals will be determined by adding together how many goals the team scores each game. These would be found in the stats as "Goals For" or "GF".

Code and Visualizations: https://github.com/oradford/data-science-portfolio/blob/main/projects/DTSC%20Project.ipynb
<img width="540" height="467" alt="image" src="https://github.com/user-attachments/assets/feace4af-82ac-44a8-b7ac-2646d7f4b173" />
<img width="532" height="391" alt="image" src="https://github.com/user-attachments/assets/b4290bc7-52ec-4164-8074-56e5c72cdff4" />



Results Explained: Looking at the first figure, we can see that the top teams in the league did in fact score the most goals. In the second figure we can see that there is a positive correlation between wins and goals scored. The data ultimately shows that there is a strong positive correlation between the amount of goals a team scores in a season and the amount of games a team wins in a season. In conclusion, we can assume that, if Chelsea continues to be one of the highest scoring teams in the Premier League, they will win a good percentage of their games and be one of the best teams in the league.

Ethics and Limitations: This dataset is limited because of the fact that I could not obtain the API that shows the data for every Premier league team. Additionally, the data from this was recorded in the 2023-2024 season and could just have been that one season's trend. One question that I would explore for this conclusion if I had more time and data is if this is the case for all sports. For example, would a team that scores 30 points per game win more games than a team that only allows 7 points per game?

Underlying Code: https://www.thesportsdb.com/ AI Usage Disclosure: Google Gemini was used in order to help debug sections of the code. Gemini was also used in order to help find the dataset. All functions were manually validated through testing.

References: TheSportsDB (2024). English Premier League 2023–2024 season lookup table. TheSportsDB REST API. https://www.thesportsdb.com/api/v1/json/3/lookuptable.php?l=4328&s=2023-2024 Sports Reference LLC. (2024). 2023–2024 Premier League stats. FBref. https://fbref.com/en/comps/9/2023-2024/2023-2024-Premier-League-Stats?utm_source=chatgpt.com Google. (2026). Gemini. https://gemini.google.com/

---
## Project 2
Cam Ward Career Analyzation - Is he as bad as people think?

Cam Ward began his college football career as an unranked 0-star quarterback playing for a poor football program in Incarnate Word. After having an electric year, he transferred to Washington State. After excelling in his time and Washington State, he received multiple offers from big schools, such as Miami where he would ultimately end up signing. In his final year, he was an electric quarterback and ended up finishing fourth in Heisman voting and was widely regarded as the number one pick. Ward was selected first overall by the Tennessee Titans in 2025 and was the day one starter. In Ward's rookie year, the team finished with a 3-14 record and was one of the worst teams in the league. However, this was largely dismissed because they were expected to be a bad team. Since the beginning of the 2026 season, the team has remained winless, and people are beginning to blame Ward. Despite the fact that Ward has one of the worst supporting casts in the league, he has received severe criticism recently, including an interview he claimed he believes he is a great quarterback and a reporter returned, "doesn't a very good quarterback have better results than you?" 

In this project, I set to find out if the performance of the team is actually a reflection of Ward's abilities or if he is a product of his surroundings. My variables are year one completion percentage, year one yards, year one touchdowns, as well as year one interceptions, and year one passer rating. This project would be a classification and a regression because it is classifying if he is going to improve year 2 or not, however, it is also calculating how much he is improving by. The source of my dataset is Pro Football Reference. Year one completion percentage is the percentage of passes players completed in their rookie seasons, year one yards is how many yards they had in their rookie seasons, year one touchdowns is the amount of touchdowns they scored, year one interceptions is how many interceptions they threw, and year one passer rating is a collection of those stats weighed to score the quarterback's performance. The lowest possible passer rating is a 0 and the highest is a 158.3. The dataset is roughly 25 quarterbacks and about 5 stats per quarterback, however the quarterbacks were selected randomly so there would not be any bias. 

To begin working with the dataset, I immediately added a new column in the dataset that is titled "Class". This column is so that I could look at each player and determine if they had improved from season one to season two. If they improved, they received a one and if they did not improve or got worse, they received a 0. Additionally, I added another column titled "Amount", that determined how much that players passer rating improved or decreased from year one to year two. You can see how many of each classification there were and the average change that class had. 

Code and Vizualizations - [[[[[DTSC Project2.ipynb](https://github.com/oradford/data-science-portfolio/blob/c5ffe6f1cb08bbce564fa329d1dfb12f026b05aa/DTSC%20Project2.ipynb)]]]
](https://github.com/oradford/data-science-portfolio/blob/6e00240029958c26f3e87b0ce99cd04cf7f6ef01/DTSC%20Project2.ipynb)

<img width="576" height="453" alt="image" src="https://github.com/user-attachments/assets/f463364d-57a8-4d72-87c9-f9dbe15e5b2a" />

Ultimately, it is hard to determine if Cam Ward will be successful in the league with just these stats and a limited amount of time. There are not many big consequences of incorrect predictions. I could predict that he is going to improve this season and be a good player in the league and be wrong, but that doesn't mean much. Where this could be an issue is if I predict that he is going to be a good player so the management pays him a lot of money and then he is bad and is a waste of money. If I predict that he will be bad and he is good, he is being significantly underpaid and could request a trade or sign with another team. A big source of bias that could come into play is that I am a big Cam Ward fan, so I am always going to try to jump to his defense. In the end, Cam Ward is predicted to be a good player and is expected to have a passer rating six points better than he did last season. However, if you look at his current stats, he is sitting at only about an 81, which is around one point better. Additionally, if you look wider scope, Patrick Mahomes was one of the analyzed quarterbacks and his passer rating went down almost 9 points between his first and second year, showing that people should judge Cam Ward a lot less as even the best players struggle early on. 

AI Usage Disclosure: Google Gemini was used in order to help debug sections of the code and to help understand what certain questions were asking. Gemini was also used in order to generate random quarterbacks in the last 10 years. All functions were manually validated through testing.


References: 
Halkias, A. G., II. (2026, September 17). Titans QB Cam Ward gets brutal reality check from reporter after bold claim. Heavy. https://heavy.com/sports/nfl/tennessee-titans/titans-cam-ward-brutal-reality-check-reporter/

Pro-Football-Reference. (n.d.). 2025 NFL advanced passing. Sports Reference. Retrieved October 4, 2026, from https://www.pro-football-reference.com/years/2025/passing_advanced.htm

Pro-Football-Reference. (n.d.). Robert Saleh record, statistics, and category ranks. Sports Reference. Retrieved October 4, 2026, from https://www.pro-football-reference.com/coaches/SaleRo0.htm

