# Jack Wu

**[Hate Crimes In NYC by Precinct Project](https://github.com/jackwu63/Hate-Crimes-Project)**
* Code that creates a choropleth map indicating the # of occurrences a crime is committed in police precincts.
* Used python to filter datasets to isolate data pertaining to precinct, year, areas

![](/images/meh.PNG)
* **Overview:** I wrote a code that would display NYC by precinct in a choropleth map. I believed that the amount of hate crimes committed would increase during the years 2020 and 2021. I preprocessed datasets to isolate data that I would use. I used pandas to read the datasets and plotly.express to create a choropleth map with a dropdown menu that would allow users to change the year(2019 to 2021).

* **Data Section:** The HC-20XX datasets were filtered to only contain the year, police precinct, amount of occurrences, and the areas where the precincts consisted.

* **Techniques:** I first used pandas to read the 3 Hate Crime datasets with usedcols="" to filter the datasets. I then saved these datasets as a separate file as they contained what I needed to create a choropleth map. I created a mask for the precinct IDs so that they would match with the precincts in the datasets. Plotly.express was used to create a choropleth mapbox that allowed me to set the locations with presets that allowed me to customize how it looked. 

* **Citations:** -[Crime Data Explorer](https://crime-data-explorer.fr.cloud.gov/pages/explorer/crime/hate-crime)
                 -[Hate Crime Arrests](https://www1.nyc.gov/site/nypd/stats/reports-analysis/hate-crimes.page)
