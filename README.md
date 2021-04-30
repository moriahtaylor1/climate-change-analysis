# Climate Change
## Project 1 - UNC Data Bootcamp
## [Shalyn Lavoie](https://github.com/shalynalavoie) | [Lauren McCarthy](https://github.com/lamccart15) | [Nicole Pierre](https://github.com/nicpie-bit) | [Moriah Taylor](https://github.com/moriahtaylor1)
### April 17, 2021

## Introduction
Rising temperatures, extreme weather, and natural disasters are experienced globally each year. These changes in our environment indicate a need for adaptability over time across the globe. Data has been gathered to better understand the nature of climate change as it relates to population growth, greenhouse gases, and temperature. Our analysis reveals that these are strong indicators of what is advancing climate change. 

## How have emissions changed over time?
##### *Analysis by Lauren McCarthy*

Global emissions have been rising over the years - with average CO2 emissions being the largest contributor overtime. The majority of greenhouse gases include Carbon dioxide (CO2), methane (CH4), and nitrous oxide (N2O). Within our dataset, there was a drastic increase in average global CO2 emissions from 128.58 million metric tons to 566.97 million metric tons over the time span of 1950 to 2019. Within this increase, there is large variability in emissions around the world with some countries contributing significantly more to overall emissions than others. 

![Average Global CO2 Emissions (1950-2019)](/Final-Images/AvgGlobalCO2.png)

![CO2 Emissions by Country (1950-2019)](/Final-Images/CountryChangeCO2.png)

In some of the already higher contributing countries, China and the US  stand out in terms of CO2 emission since the 1950’s. Even when considering a shorter span of time from 2000 to 2013, there is a notable increase in CO2 emissions (454.89 million metric tons to 647.04 millions metric tons). It is clear that emissions have been increasing over time around the world.

![Average Global Emissions Overtime (2000-2013)](/Final-Images/AvgGlobalSplit.png)

## Is there a correlation between population growth and climate change?
##### *Analysis by Shalyn Lavoie*
Population levels naturally vary across countries. As seen in the next graph, Germany, Japan, Singapore, and Ukraine had a net negative decline in population growth while other countries had a positive increase in population growth from 1950 to 2013.

![Population Growth (1950-2013)](/Final-Images/Populationgrowth.png)

Overall, there has been an average increase in temperature over the years in looking at the Average temperatures from 2000-2013 bar graph. Looking at the correlation coefficient of 0.52, we can see that the population growth and average temperature are moderately correlated. Taking it a step further in looking at the model with an r-squared value of 0.26, we have substantial representation of data of average temperature versus population growth. Comparing population growth to average temperature the data shows that there is a correlation.

![Population Growth % vs. Temperature (2000-2013)](/Final-Images/populationgrowthvstemperature.png)

## How does temperature adn rate of emissions relate to extreme weather?
##### *Analysis by Nicole Pierre*
Extreme weather is not uncommon here in the United States. For example, in the year 2020, there was a record number of hurricanes. One possible explanation for this extreme weather is climate change.

The following bar graph compares the average temperature from the year 2000 and 2013, showing that most countries have had a multiple-degree increase in average temperature. Canada had the highest increase in average temperature (42F to 46F), while Germany had the highest decrease in average temperature (51.7F to 50.2F). Referencing the Average Global CO2 Emissions line graph from question 1, the amount of CO2 emission has significantly increased from 1950 to 2020. As CO2 emissions increase, the average temperature increases overall meaning there is a positive correlation between the two. 

![Average Temperatures: 2000 vs 2013](/Final-Images/AvgTemp_per_country.png)

As CO2 and temperature increase there are spikes in the number of disasters. The line graph below shows that every 2-3 years there is a spike in the number of disasters. 

![Number of Disasters (2000-2019)](/Final-Images/num_of_disasters.png)

This last graph demonstrates the total affected globally, indicating that there is not a spike in those affected in the same years that the number of disasters spike. This shows that the disasters are not getting worse or more dangerous but they are just happening at a higher, more frequent rate. We can conclude that the increase in CO2 emissions leads to an increase in average temperature which results in a higher number of disasters each year.

![Number of People Affected Globally by Natural Disasters](/Final-Images/NatDisaster_deaths.png)

## What countries are most at-risk of climate change?
##### *Analysis by Moriah Taylor*
In the United Nations Framework Convention on Climate Change (UNFCCC), countries are organized by region but also into special interest groups. A few of these groups are Least-Developed Countries (LDC), Small Island Developing States (SIDS), and Organization of Petroleum-Exporting Countries (OPEC). In these graphs, Bangladesh represents the LDC group, Dominican Republic represents the SIDS group, Saudi Arabia represents the OPEC group and Germany represents the European Union (EU).

![GDP, Imports, Exports](/Final-Images/gdp_all.png)
![GDP, Imports, Exports - A Closer Look](/Final-Images/gdp_smaller_countries.png)

The plots above show how the economies of the US, China, and Germany are drastically larger than those of Bangladesh, Dominican Republic, and Saudi Arabia. 

The emissions plot below shows that the United States and China are significant contributors of greenhouse gases. The other 4 countries have 1,000 million tonnes of CO2 equivalent of greenhouse gas emissions or less, while the United States stays steady around 6,000 million tonnes, and China shockingly increases from about 4,000 million tonnes to nearly 12,000 million tonnes from 2000 to 2013. 

The temperature plots (below) show that the average temperatures for China and the United States increased 2-3 degrees Fahrenheit from 55 degrees to 57-58 degrees. The plots also show that the smaller countries all average temperatures above 78 degrees Fahrenheit and increased 1-2 degrees from the year 2000 to 2013. All together, this information indicates that these smaller countries which are contributing astronomically less to global emissions and have much smaller economies are still suffering the effects of these emissions in the form of temperature increase. Although China and the United States have temperatures increasing as well, they have the financial ability to be able to increase their preparedness for extreme weather through early warning systems and structural building changes. These smaller countries do not have the ability to fund these types of projects and are going to suffer because of it, especially the small island developing states which are directly and harshly affected by sea level rise and tropical storms.

![Emissions and Temperatures](/Final-Images/emissions_and_temps.png)

## Conclusions and Implications
* Emissions continue to rise across the world, with some countries having a larger impact on the rising levels of greenhouse gases. 
* Increased emissions leads to an increase in temperatures, which can result in more extreme weather events. Least-developed countries and small island countries are more vulnerable to these events.
* The world must continue to assess the changing climate and act responsibly to reduce the damage already made to our environment, as well as limit further damage. 

## Reflections and Considerations
* Challenges:
  * Lack of consistency among countries
  * Narrowing down a broad topic to a few specific questions
  * Multiple large datasets
  * Missing data
* Other Directions:
  * Adding information from an API
  * Finding accurate data on precipitation levels

## Data Resources
* **General Statistics (Population, GDP, etc):** [*The World Bank DataBank*](https://databank.worldbank.org/home.aspx!)
* **Emissions:** [*Our World in Data*](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions)
* **Temperature:** [*Kaggle*](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data!)
* **Disasters/Extreme Weather:** [*EM-DAT International Disasters Database*](https://www.emdat.be/)
