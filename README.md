# NBA_Python_Power BI_Analysis
NBA analysis project using Python and Power BI 

<h3>Tools Used</h3>

- Data - web scraping
  
- Data Cleaning & Analysis - Python - Visual Studio Code - Jupyter notebook

- Data Visualization - matplotlib python library for graphs


<h3>Questions</h3>


- Who are the players with the best (Points, rebounds, blocks, Assists, steals, min per game) from 1991 to 2023?  
  
- Who are the players with the best season (Points, rebounds, blocks, Assists, steals, min per game) from 1991 to 2023? 

- What team with the most winning games and fewer losing games from 1991 to 2023? Why?



<h3>Python Code</h3>
<h4>this project have 3 layers</h4>

- Web scraping to get the data.
  
- Cleaning and preparing the data.

- Exploring and analyzing the data.

  <h4>WEB SCRAPING</h4>

- We start by scraping all the webpages of the mvp and get the mvp tables from it (1991 to 2023) and then merge all data in one (mvp.csv) file.

- Scrap all the webpages of the player stats, get all the player stats tables from it, and merge all data in one (player.csv) file.
  
- Scrap all the webpages of the teams, get all the team's data tables from it, and merge all data in one (team.csv) file.



<h4>CLEANING AND PREPARING THE DATA</h4>

- Clean the data from unwanted columns, signs

- Some players have more than one row of data per year with different teams so clean that by keeping the total stats with the final team name 
  
- Combine player data with MVP data as a combine.csv file

- Replace the nan value of the MVP columns after merging with player data with (0) ( because nan of the mvp table means the the player did not get any votes for the MVP race )

- Clean the team data from any unwanted rows and signs

- Correct the team names

- Merge the combine.csv data with team data as stats.csv

- Convert all columns types to numerical type.


<h4>EXPLORING AND ANALYSIS THE DATA</h4>

Columns name: TPTS (total points), TAST (total assist), TTRD (total rebound), TSTL (total steal), TBLK (total block), TMP (total minutes played). PTS (points), AST (assist), TRD (rebound), STL (steal), BLK (block), MP (minutes played)


<h4>Summary of Findings</h4>
<h5>Who are the players with the best (Points, rebounds, blocks, Assists, steals, min per game) from 1991 to 2023 ?</h5>
<p>- The highest points have been scored by Lebron James in this data and that is right because he started playing after 1991 and still playing now(2023). </p>
<p>- The highest assists have been accomplished by Jason Kidd in this data. that same right because the position he plays is point guard. </p>
<p>- The highest rebounds have been accomplished by Tim Duncan in this data. Tim Duncan is one of the best players in NBA history and he played as the center.</p>
<p>- The highest steals have been accomplished by Jason Kidd in this data.</p>
<p>- The highest blocks have been accomplished by Dikembe Mutombo in this data.</p>
<p>- The highest minutes played have been accomplished by Lebron James in this data. that is because he has been playing starter since his first year for the Cleveland Cavaliers with a high using rate and he is currently in his 20th season.</p>

<h5>WHO ARE THE PLAYERS WITH THE BEST AVERAGE (POINTS, REBOUNDS, BLOCKS, ASSISTS, STEALS, MIN PER GAME)SEASON FROM 1991 TO 2023 ?</h5>
<p>- James Harden's best average point season (2019)</p>
<p>- John Stockton's best average assists season (1991)</p>
<p>- Dennis Rodman's best average rebounds season (1992, 1994)</p>
<p>- Alvin Robertson's best average steals season (1991)</p>
<p>- dikembe mutombos' best average block season (1996)</p>
<p>- Anthony Mason's best average minutes played season (1997)</p>
<p>  </p>
<p>- From looking at the graphs most of the the top 5 highest average seasons in all categories  happened in the 90s</p>





<h5>WHAT TEAM WITH THE MOST WINNING GAMES AND LESS LOSING GAMES FORM 1991 TO 2023? WHY?</h5>
<p>-  that San Antonio Spurs is the best team with the highest winning games and the lowest losing games from 1991 to 2023</p>
<p>- From the rebound, blocks, and turnovers we can find out that the Spurs were one of the best defensive teams with amazing strategy and very efficient gameplay.</p>
<p>- with the second place in assists. despite being second last in points and the last in steals. spurs steal and manage to control the game flow. As we see Spurs is an efficient team with strong defense.</p>




