# Expanding Your Restaurant - Minimum Viable Product (MVP)
### Nicholas Dell'Aquilo

## The Problem
You own an independent, casual dining restaurant and are looking to expand to a new location in New York City, but there are many questions to consider:

* What kinds of restaurants are already in the city?
* Where are most restaurants located?
* What kinds of food are served the most?
* What is the nutrition information of the items you are competing with?

...and so on. It can be difficult to comprehend all of this information, so being able to do so should have an impact on how you choose to do business.

## Impact Hypothesis
By better understanding the field of competition of food service in New York City, you can make informed decisions about where to open a new location, and what to serve on your menu to stay competitive. 

## Datasets
A conscious choice for this project is to source data from New York City's [Open Data](https://opendata.cityofnewyork.us/). These datasets are public and free to use, held to a specific standard of quality by law, and consistently updated periodically. Their ease of access lowers the barrier of entry for this method of analysis, lowering the risk of losing resources on this initiative. The specific datasets used include [Restaurant Applications](https://data.cityofnewyork.us/Transportation/Open-Restaurant-Applications/pitm-atqc) for geographical data and [MenuStat](https://data.cityofnewyork.us/Health/DOHMH-MenuStat/qgc5-ecnb) for nutritional data.

## Preliminary Analysis
Exploratory analysis and vizualization of the data has shown some clear trends.
![image](https://user-images.githubusercontent.com/22899761/119559664-fc312c80-bd70-11eb-92e0-231e976f6f3a.png)
*The map appears overly cluttered when at this size, but is much more legible when zoomed in.*

According to geographical information in the dataset, we can display a map of dining locations in New York City that have applied for outdoor seating. This information can be used to make informed decisions about where a new location might be located- in a less crowded area, for example.

![image](https://user-images.githubusercontent.com/22899761/119561370-14a24680-bd73-11eb-8eaa-32e2fc573a7a.png)

Nutritional information in the dataset can be used to determine the development and inclusion of new menu items. This could be taken further and used in promotional materials or advertisements- offering a better alternative to a competitor is a great way to generate interest.

## Future Analysis
The level of analysis possible is limited by the information available in these datasets. Further analysis would require the acquisition of more information, such as the types of locations in certain areas, and what types of items tend to be more commonly sold at certain locations. For example, a model could be created that defines the relationship between certain items being available on a menu and some metric of success.
