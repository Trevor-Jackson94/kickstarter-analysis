# Kickstarting with Excel

## Overview of Project
This project was carried out to help Louise better understand the kickstarter campaign market in relation to her project *Fever*. Our analysis gave insight into similar projects and their outcomes based on launch dates and on fund raising goals. 

### Purpose
With the following analysis of recent Kickstarter data we intended to simplify the data to better understand how Louise's project *Fever* fared in regards to other funding projects of similar background. A better understanding of how competing projects did in terms of funding based on their launch dates and total funding goals will help Louise have an idea how well her project did. She will gain insight about her project in relation to other *plays* being funded through Kickstarter and whether she did better or worse than others based on when she launched her Kickstarter project and what she set her Kickstarter goal at. 

## Analysis and Challenges
In our analysis we created a workable pivot table and pivot chart showing outcomes of successful, failed, and canceled, based on whether or not the project met it's funding goal and organized these outcomes by month that the campaign started. Some challenges encountered during this analysis include the determining the outcomes based on funding goals and total funds pledged. Another challenge, was sorting out categorically which projects were most relevant in relation to Louise's play *Fever*. A *subcategory* column was created using the *Convert Text to Columns Wizard* in Microsoft Excel to help further limit the projects being analyzed against *Fever*.

After analysis was done based on launch date we created a detailed look at similar project outcomes based on their funding goals. During this analysis the percentage of successful, failed, and canceled projects were calculated for the following intervals:
Less Than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
50000 or more

A challenge during this process was accurately pulling the total numbers of successful, failed, and canceled projects only in the *plays* subcategory and in the determined funding goals intervals. After rigorous trial and error the correct coding for the =COUNTIFS() command was determined and a line graph was developed to simplify the data and see how similar projects fared in funding based on funding goals.  

### Analysis of Outcomes Based on Launch Date
The full analysis of Outcomes Based on Launch Date can be found in the *Theater Outcomes by Launch Date*. This analysis includes a Pivot Table using a total count of the outcomes of *theater* projects in the columns in relation to the months these projects were created on Kickstarter. The possible outcomes include successful, failed, and canceled. The data created from this analysis shows the highest number of successful projects occurred in May and June. During these months the ratio of successful to failed projects is also significantly higher than other months as seen on the pivot chart created from the data. 

![Theater Outcomes Based on Launch Date](https://github.com/Trevor-Jackson94/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
After analyzing the data based on launch date, the data was analzyed based on funding goals. The number of projects in the *plays* subcategory were counted out based on outcome, and filtered into specific funding goal ranges. These ranges are as follows:
Less Than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
50000 or more

From this data we created percentages of projects that were successful, failed, and canceled for each funding goal range. This information was then visualized in a line chart seen below.

![Outcomes Based on Funding Goal](https://github.com/Trevor-Jackson94/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

This data shows that the most successful percentages of projects tend to have funding goals less than $15000. After $15000, successful funding goal percentage sharply drops and stays relatively low, except for the $39,999 to $44,999 range. 

### Challenges and Difficulties Encountered
As previously mentioned, there were difficulties encountered when creating the subcategory column to help pull out more relatable data to Louise's *Fever*. This was overcome by using the Text to Column Wizard in Excel. There were also some challenges in defining the correct coding for the =COUNTIFS() functions that pulled out the number of successful, failed, and canceled projects within the defined funding goal ranges, and only the projects that fell into the *plays* subcategory. Trial and Error and some persistence helped rectify the difficulties encountered during the process.

## Results
Based on the analysis of Outcomes Based on Launch Date, we can see now that May and June are the best months to start a Kickstarter campaign for a *theater* project by a significant margin. While we can see there are much higher numbers of projects started in these months overall, we also see a higher ratio of successful to failed campaigns during these months. We can conclude from this that even though there is a higher number of failed projects in May and June there is still a better ratio of successful projects and these months are the best to start a *theater* Kickstarter campaign. In regards to the analysis of Outcomes Based on Goals, projects in the *plays* subcategory tend to reach their funding goals at a much higher rate when the goals are less than $15,000. There is also a range from $35,000 to $44,999 where the success rate goes above 50%. Overall, to set the project up for a successful campaign on Kickstarter, it's recommended to set the funding goal to $15,000 or less. Projects with funding goals above $15,000 tend to have very low or sporadic success rates. The data is limited by broad nature of the *plays* category. We could gain some more relatable information is the *plays* category was further separated into the themes of the plays or type of plays. The data is also limited because the Outcomes by Funding Goal analysis didn't take into account the percentage of funding received and also the average donation of donators. Some projects may have received lump sums of funding from single investors that complete their goals, instead of having a more widespread interest. To further analyze the dataset, a table could be completed to show what percentage of Kickstarted campaigns reached their goal that did not receive *spotlight* as well as percentage of campaigns that reach their goal that did receive *spotlight*. It would give insight into the value of the *spotlight* attribute. 
