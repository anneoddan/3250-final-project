# BAIS:3250 Final Project
**Author(s):** Anne Oddan, Brendan Sullivan, Megan Tetrick

**Description:** 
The National Football League (NFL) is a professional American football league comprising 32 teams divided into two conferences: the American Football Conference (AFC) and the National Football Conference (NFC). Each conference is further segmented into four divisions, each consisting of four teams. Each of these teams plays a 17-game regular season (they previously played 16-game regular seasons prior to 2021). Across these 17 games, teams play for a spot in the playoffs, where the top teams from each conference compete to reach the Super Bowl, the NFL’s championship game.

Our analysis focuses on examining the relationship between player salaries and team success. Player salaries in the NFL vary significantly based on a player’s position, skill level, experience, and contract negotiations. Conversely, team success is typically assessed by win-loss records, playoff appearances, and ultimately, their performance in the postseason.

The issue we are seeking to explore is whether a high payroll, which generally signifies higher salaries for players, correlates with enhanced team performance. While it may seem logical that more expensive players would produce better results, various factors might influence the outcome. Through our analysis, we aim to uncover patterns or insights into how player compensation relates to overall team success.

### Links

1926 - 2024 NFL Scores--- https://www.kaggle.com/datasets/flynn28/1926-2024-nfl-scores 

NFL TEAMS scrapped --- https://www.spotrac.com/nfl/teams


### Data Dictionary
| Field Name | Description |
| ------------- | ------------- |
| Date | The date the game was played |
| Day of the week | The day of the week the game was played |
| Winning Team Name | The winning team|
| Loosing Team Name | The loosing team |
| Winning Team Score | The number of points by the winning team |
| Losing Team Score | The number of points scored by the losing team |
| Type | The type of game |
| Year | The season year |
| Winning Rank | The winning team's salary cash ranking by season |
| Winning Team Record | The winning team's win - loss - tie record |
| Winning Signed Players | Total number of signed players on the winning team |
| Winning Avg Age | Average age of the signed players on the winning team |
| Winning Active Cash | The money that is currently allocated to players and counts against the winning team's salary cap for the season |
| Winning Dead Cash | Money that is still owed to players from previous contract but is no longer counted against the winning team's active salary cap |
| Winning Total Cash | The total amount of money players will earn in a given season, including both active and dead cash, of the winning team |
| Loosing Rank | The losing team's salary cash ranking (1 being the hgihest total cash salary) by each season |
| Losing Team Record | The losing team's win-loss-tie record
| Losing Signed Players | Total number of signed players on the losing team |
| Losing Avg Age | Average age of the signed players on the losing team |
| Losing Active Cash | The money that is currently allocated to players and counts against the losing team’s salary cap for the season |
| Losing Dead Cash | Money that is still owed to players from a previous contract but is no longer counted against the losing team’s active salary cap |
| Losing Total Cash | The total amount of money players will earn in a given season, including both active and dead cash, of the losing team |







## Folders
### [Documents](Documents)
- **Project Proposal Data Wrangling.docx** — Project proposal submitted.
- **Data Wrangling Check In.pdf** — Check-in assignment slides submitted.
- **Final Report Data Wrangling.docx** — Final report submitted.

### [code](code)
Contains code used for the project
* **[juypter_notebooks](code/juypter_notebooks):** sub-folder containing Jupyter notebooks (.ipynb) used for the project
- **FINAL Project Analysis.ipynb** — Performance metrics for models used in classifier regression analysis, while also doing visuals.
- **Project Data Integration FINAL.ipynb** —Integrated the scraped and kaggle datasets.
- **Scrape, Clean, Integration FINAL.ipynb** —Scrapped and cleaned the scraped data.
  
### [data](data)
Contains data used for the project
* **[raw data](data/raw_data):** sub-folder containing the original, unclean data for the project
* **1926-2024_COMBINED_NFL_SCORES.csv** — Original data from Kaggle.
* **nfl_salary_cash_2020_2024.csv** — Scraped original data from website.

* **[final data](data/final_data):** sub-folder containing the final, cleaned data for the project
* **cleaned_nfl_data.csv** — Includes date, day of the week, winnign team name, loosing team, winning team score, loosing team score, type, year, team name, rank, team, record, singed players, average age, active cash, dead cash and finally total cash.
* **combined_nfl_data.csv** — Includes all data combined.
* **nfl_salary_cash_2020_2024.csv** — Includes team information with their cash standings (active cash, dead cash, and total cash).
* **nfl_team_data.csv** — Includes information about each team, location, and season attached to that row. 

