# final_project_Tim_Dwyer - The correlation between Low Income and Unhealthy Diets
This is for my final project in telling stories with data.

## Outline of Final Project

### Summary - DONE
For my final project, I am telling a story on how areas with lower income have higher obesity rates and lower food environment indices. Food Environment Indices measures people's access to healthy foods through measuring low income and how close people are to a grocery store. My wife and I have made it a mission to start eating more balanced meals this summer. When our grocery store spending nearly doubled, we realized that eating healthy is very expensive. Therefore, I wanted to research if low income areas struggle more with obesity and finding healthy foods.

### Outline of Major Elements - DONE

User Story:
As a reader, I want people living in the United States to understand the health challenges for low income areas so that I can work to improve their ability to make healthy choices through food.

Call to action:
I can do this by donating to charities already working to help children in these areas, and challenging government representatives to start making changes.

0. I am considering starting the story with a chart showing how the United States is one of the most wealthy countries in the world. This would start my audience on a positive note before jumping into the more sad parts of the story.
1. Start with maps of the USA for each data elements. This will help show the background and lay the foundation. This section should pull the audience to a more negative place.
    A.income map of the United States (Dark green as Highest to Light green as lower)
    B. Show an obesity map of the United States (Dark blue as lowest?? to light blue as highest?? - does this make sense to have dark be good for all of the maps?)
    C. Show an environmental food index map of the United States (Dark orange as highest to light orange as lowest)
2. Dig in further at a more detailed grain by looking at the top 25 and bottom county's by income in 2015 and see if the other metrics align. See if the trends are improving or not inn 2016 and 2017. This will further pull the story to a more sad place as they see the connection and the need for change
3. Do a similar analysis to number 2 for PA since it is where CMU is. This is probably optional, but would connect more to the class as an audience.
4. Call to action - Donate to charities that are providing lunches to children in low income areas and talk to your government about making changes about healthier options. This should create a positive ending by giving the audience power to start making a difference.


## Initial Sketches

We've explored how sketching can be a great way to help solidify your ideas into design choices, and for your proposal you'll be creating sketches that outline your initial thoughts for your final project.  You may choose to present your sketches and integrate them into Part I of your final project in whatever fashion you feel makes the most sense - but they should be clear enough to be understandable to someone that has little to no contextual background for your project.  Your sketches should mimic aspects of your outline, and build on the resounding message you want to make clear through your project.  Build in elements of your anticipated story structure for your project.  Your sketches themselves do not have to be visually correct / accurate and you may use whatever method makes the most sense to you (hand-drawn, digital, etc.). 


## The Data - DONE

I found county level data for adult obesity and enviormental food index for the years 2014 - 2018 on Data USA. The Data USA website actually has a cool feature where it will merge the datasets together, so I actually only had to download one excel file. 

Source of original data from: "Data USA." https://datausa.io/

I then needed to find county level income data. I found this on the U.S. Bureau of Economic Analysis website. 

Source of original data from:  "Personal Income." U.S. Bureau of Economic Analysis, May 2019.https://www.bea.gov/

Next, I needed to merge the two datasets. I did this by editing the income data to have the same format of county, state. Then, I used a vlookup to add the income columns to the obesity and food index data. The match was not perfect though. There was about 129 counties in the obesity and environmental food index data that did not have income data. Since this number is small compared to the overall number of counties (over 3,140), I removed these rows to allow for a cleaned dataset. Since the Data USA data contained extra years, I deleted 2014 and 2018 since they are not needed in the analytics.

I plan on using this combined data to see if there is a relationship between income, obesity, and environmental food index through data visualizations. I will do this by comparing the income from 2015 to the environmental food index and obesity from 2015 to see if more wealthy areas have lower obesity rates and higher food indices, and if they opposite is true for low income areas. I will leverage the data to do the analysis for 2016 and 2017 to see what if they wshow simlar results.


## Method and medium - DONE

As noted above, the first part of completing my final project was finding my datasets. I then needed to combine and clean the datasets to create on final flat file. I completed this using excel. I have also finished my inital sketches, which are also shown above.

To complete the remaining steps of the project, I plan on leveraging shorthand to bring the whole story together. I will use the tools we have learned throughout the class to create some of my initial and final visualizations. I have found that uploading the data into tools, such as infographics and rawgraphs, and trying a few different chart types and colors helps me continue to learn more about the datasets. This will help me continue to refine my sketches and story. I plan on sharing my initial story with a few people to recieve feedback to further refine its elements.

