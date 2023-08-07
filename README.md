# Analyzing-olympics_dataset-using-sql

## About Dataset
Context
This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016.
The data wasgotten from **Kaggle**

Note that the Winter and Summer Games were held in the same year up until 1992. After that, 
they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on. 
A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.

### Athlete_event table

The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events).
The columns are:

ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimeters
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA

### Noc_regions table
The file Noc_regions.csv contains 230 rows and three columns. Each rows cotaining the National olympic committee 3-letter code. 
The columns are:
NOC - National Olympic Committee 3-letter code
region - Country name 
Note- The province or state of the country.

###   Questions answered using the dataset
How many olympics games have been held?

List down all Olympics games held so far.

Mention the total no of nations who participated in each olympics game?

Which year saw the highest and lowest no of countries participating in olympics?

Which nation has participated in all of the olympic games?

Identify the sport which was played in all summer olympics.

Which Sports were just played only once in the olympics?

Fetch the total no of sports played in each olympic games.

Fetch details of the oldest athletes to win a gold medal.

Find the Ratio of male and female athletes participated in all olympic games.

Fetch the top 5 athletes who have won the most gold medals.

Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).

Fetch the top 5 most successful countries in olympics. Success is defined by no of medals won.

List down total gold, silver and broze medals won by each country.

List down total gold, silver and broze medals won by each country corresponding to each olympic games.

Identify which country won the most gold, most silver and most bronze medals in each olympic games.

Identify which country won the most gold, most silver, most bronze medals and the most medals in each olympic games.

Which countries have never won gold medal but have won silver/bronze medals?

In which Sport/event, India has won highest medals.

### Database used for the sql analysis

The database used for the sql analysis was Postgresql.



