# Football Leagues
Automatization process of creating whole data model and reporting.

All you have to do is copy/paste to script an URL from transfermarkt.com league profile.
You can compare data of thousands leagues from around the world.

I did a script with Jupyter Notebook, which creates whole data model. In general the process looks like:
- Extracting data from tranfermarkt.com using webscrapper,
- Transforming and normalize data process,
- Creating fact tables and lookup tables,
- Saving data to .csv file, (if you run script again, then data will append to the same .csv file)

Also I finished data modeling process with Power Query.

For report finalization I used Power BI, also there are included couple DAX measuers
