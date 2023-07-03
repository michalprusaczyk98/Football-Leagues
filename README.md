# Football Leagues
## Automatization process of creating whole data model from scratch and reporting.
## [Example of interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTliMDE3NDEtYWMyNy00NTEwLTk2ZjEtNTkzMjE0ZGE5YTE4IiwidCI6ImFjYjdlMzMyLWFjMTctNDA5ZC04OWZiLWE2MTQxNjEyNGM0YSIsImMiOjl9)
### [Creating Data Model Script](https://github.com/michalprusaczyk98/Football-Leagues/blob/main/Football_Leagues_Players.ipynb)
### [Creating Data Model Script #2](https://github.com/michalprusaczyk98/Football-Leagues/blob/main/Football_Leagues_Stats.ipynb)

All you have to do is copy/paste an URL from transfermarkt.com league profile to script.
You can compare data of thousands leagues from around the world.

I did a script with Jupyter Notebook, which creates whole data model. In general the process looks like:
- Extracting data from tranfermarkt.com using webscrapper,
- Transforming and normalize data process,
- Creating fact tables and lookup tables,
- Saving data to .csv file (if you run script again, then data will append to the same .csv file)

Also I finished data modeling process with Power Query.

For report finalization I used Power BI, also there are included couple DAX measuers
