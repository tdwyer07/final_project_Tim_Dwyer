# final_project_Tim_Dwyer - The correlation between Low Income and Food Insecurity
This is for my final project in telling stories with data.

## Outline of Final Project

### Summary
For my final project, I am telling a story on how areas with lower income have higher food insecurity rates. I plan on starting with the full USA view and then drilling down to Pennsylvania since the target audience is residents in Pennsylvania. I hope talking about the areas near where people currently live helps make them connect to the story and the call to action.

### Outline of Major Elements

User Story:
As a reader, I want people living in the United States, specifically Pennsylvania, to understand the health challenges for low income areas so that people can work to improve the situation for those people.

Call to action:
I can do this by donating to charities already working to help children in these areas, and challenging government representatives to start making changes.

1. Start with some high level statistics on how many people/children are hungry in USA. This is a hook showing and should pull people in by the surprise at the significance of the numbers.
2. Show a visualization explaining how the United States is one of the most wealthy countries in the world. This would start my audience on a positive note before jumping into the more sad parts of the story.
3. Show a few maps of the USA . This will help show the background and lay the foundation and start to connect the idea of income and food insecurity. This section should pull the audience to a more negative place.
    A.income map of the United States
    B. Show an environmental food index map of the United States 
4. Drill down to show maps of Pennsylvania to connect more personally with my audience. This should keep the audience in a negative place.
    A. income map of Pennsylvania
    B. Overall food insecurity map of Pennsylvania
    C. Childhood food insecurity map of Pennsylvania
5. Top 10 and Bottom 10 Pennsylvania county by Income against Child Food Insecurity Rate
Create a chart showing the top income counties and bottom income counties in Pennsylvania compared to childhood food insecurity rates to see if there is a distinct difference in the groups. This should show the bottom line that low income areas clearly have higher childhood insecurity rates. This should be very negative for the audience and the low point of the presentation pushing them to want to donate to support the areas through the charities in the call to action.
6. Call to action - Donate to charities that are providing food to children and adults in low income areas. This should create a positive ending by giving the audience power to start making a difference.


## Initial Sketches

Below are some of my initial thoughts for the project.


Map of 2015 Environmental Food Index

<iframe title="Environmental Food Index 2015" aria-label="USA counties (2014) choropleth map" id="datawrapper-chart-lzL3m" src="//datawrapper.dwcdn.net/lzL3m/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>

Map of 2015 Income

<iframe title="Income 2015" aria-label="USA counties (2014) choropleth map" id="datawrapper-chart-MARrd" src="//datawrapper.dwcdn.net/MARrd/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="400"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>

I like the idea of the first three charts. I think I need to refine them some though. I am also starting to realize that 3 years of data is a lot and maybe I should just concentrate on one year, perhaps 2017.

Top Income Counties 2017

<iframe title="Top 10 Income" aria-label="Dot Plot" id="datawrapper-chart-ecuBO" src="//datawrapper.dwcdn.net/ecuBO/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="320"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}})}();</script>

This is a very initial sketch of comparing the top 10 income counties against the average income. It also contains obesity rates and environmental food index rates against the average. Clearly the scales of this chart do not work. I am thinking maybe have a different chart for all 3 and include the top 25. I also like the idea of doing this for the bottom 25.

Looking at Top and Bottom Income USA Counties

<div class="infogram-embed" data-id="67881604-81d1-4dc2-81dc-4224b1819382" data-type="interactive" data-title="Untitled infographic"></div><script>!function(e,t,s,i){var n="InfogramEmbeds",o=e.getElementsByTagName("script")[0],d=/^http:/.test(e.location)?"http:":"https:";if(/^\/{2}/.test(i)&&(i=d+i),window[n]&&window[n].initialized)window[n].process&&window[n].process();else if(!e.getElementById(s)){var r=e.createElement("script");r.async=1,r.id=s,r.src=i,o.parentNode.insertBefore(r,o)}}(document,0,"infogram-async","https://e.infogram.com/js/dist/embed-loader-min.js");</script><div style="padding:8px 0;font-family:Arial!important;font-size:13px!important;line-height:15px!important;text-align:center;border-top:1px solid #dadada;margin:0 30px"><a href="https://infogram.com/67881604-81d1-4dc2-81dc-4224b1819382" style="color:#989898!important;text-decoration:none!important;" target="_blank">Untitled infographic</a><br><a href="https://infogram.com" style="color:#989898!important;text-decoration:none!important;" target="_blank" rel="nofollow">Infogram</a></div>


I like these scatter plot a bit better. Still need to refine it a bit though. You can clearly see that there is a distinction in obesity rates and environmental food indices between the high and low income groups. As expected, the average falls pretty much in the middle on both charts. In the next version of the sketches, I want to look into doing a similar chart for PA counties.



## The Data

I found county level data for adult obesity and enviormental food index for the years 2014 - 2018 on Data USA. The Data USA website actually has a cool feature where it will merge the datasets together, so I actually only had to download one excel file. This data was leveraged in the USA food environmental index graph.

Source of original data from: "Data USA." https://datausa.io/

I then needed to find county level income data. I found this on the U.S. Bureau of Economic Analysis website. This data was used in the Pennsylvania and USA income graph.

Source of original data from:  "Personal Income." U.S. Bureau of Economic Analysis, May 2019. https://www.bea.gov/

I pulled the data for the introduction on overall hunger in the United States from Feeding America. I also found childhood and overall food insecurity rates for Pennsylvania on one of their sites. I leveraged this data when building some of the Pennsylvania graphs.

Sourced of original data from: "Feeding America." Feeding America, 2019. https://www.feedingamerica.org/

Sourced of original data from: "Feeding America." Feeding America, 2019. https://public.tableau.com/profile/feeding.america.research#!/vizhome/2017StateWorkbook-Public_15568266651950/CountyDetailDataPublic

I used the OECD data to get data for comparing average incomes at a country level. This helped me show that USA is one of the wealthier countries in the world

Source of Data: “Average Wages.” OECD Data, 2019. https://data.oecd.org/earnwage/average-wages.htm 

Next, I needed to merge the income and environmental food index data (and obesity data when it was part of the story). I did this by editing the income data to have the same format of county, state. Then, I used a vlookup to add the income columns to the obesity and food index data. The match was not perfect though. In these cases, the data was left blank since this number for each of the columns is small compared to the overall number of counties (over 3,140). Since the Data USA data contained extra years, I deleted 2014 and 2018 since they are not needed in the analytics. I defined FIPS code which is used in the map visualization tool for data wrapper. This was defined using the right 5 digits ID Geography from Data USA.

I plan on using this combined data to see if there is a relationship between income and environmental food index through data visualizations. I will do this by comparing the income from 2017 to the environmental food index and obesity from 2017 to see if more wealthy areas have lower food insecurity rates, and if they opposite is true for low income areas. As discussed in the outline, I then want to look more closely at Pennsylvania.


## Method and medium

As noted above, the first part of completing my final project was finding my datasets. I then needed to combine and clean the datasets to create on final flat file. I completed this using excel. I have also finished my inital sketches, which are also shown above.

To complete the remaining steps of the project, I plan on leveraging shorthand to bring the whole story together. I will use the tools we have learned throughout the class to create some of my initial and final visualizations. I have found that uploading the data into tools, such as infographics and rawgraphs, and trying a few different chart types and colors helps me continue to learn more about the datasets. This will help me continue to refine my sketches and story. I plan on sharing my initial story with a few people to recieve feedback to further refine its elements.

