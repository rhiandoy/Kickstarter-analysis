# Kickstarting with Excel Challenge

## Overview of Project
	
	In this challenge, we used our Kickstarter campaign workbook to analyze the outcomes under the "Theater" category based on 
  data from the launch datesas well as from the funding goals.
  We created a new worksheet which included a pivot table and line graph to visually observe the outcomes over a 12 month period. 
  The other worksheet created in this challenge categorized the outcomes within a specific range of the funding goals so that we could determine percentages of successful, failed, and canceled campaigns. 

### Purpose
	The purpose of this challenge was to use our newfound knowledge of Excel to visualize the outcomes of the Kickstarter 
  Campaigns. 
  We mainly focused on the outcomes, "successful, "failed" and "canceled" and the numerical data associated within the "Theater" category. 
  By creating visuals for this data, we are then able to help Louise choose the best month to launch a funding campaign and what a more successful goal range would be.

## Analysis

### Outcomes Based on Launch
	To analyze the information given in the Kickstarter worksheet, a pivot table was created in a new sheet representing 
  the "Theater" category with data pulled from the outcomes and the dates that the campaigns were created. Through this information a line graph was created to visually
  represent the successful, failed, and cancelled campaigns by each month of the year. 
![Outcome By Launch Date](https://github.com/rhiandoy/Kickstarter-analysis/blob/0067e9eefecbf37dd72a142e410a62be5ce8f395/Theater_Outcomes_vs_Launch.png)
### Outcomes Based on Goals
	After analyzing based on launch dates, we looked at the outcomes based on goals. The data for the outcomes were calculated 
  into a table in a new sheet based on a specific range of the goal provided in the first column. 
  The COUNTIFS() formula was used to pull information from the Kickstarter worksheet. For the following formula we found the sum 
  of total projects for each goal range, using SUM(). The final forumla used was =ROUND() to obtain the percentage of the outcomes again based on their range. From there, another line graph was created to represent those percentages based on the goals. 
![Outcomes Based on Goal](https://github.com/rhiandoy/Kickstarter-analysis/blob/0067e9eefecbf37dd72a142e410a62be5ce8f395/Outcomes_vs_goals.png)

### Challenge	
	The greatest challenge I faced during this analysis was creating the COUNTIFS() formula on the worksheet, "Outcomes 
  Based on Goals". It took multiple tries to get the correct formula inserted in the first cell. I tried to drag down the formula and fill in the different cells in a fast and sloppy way which resulted in small errors when trying to change the information. I also tried to fill in across which also resulted in small errors that were not noticable at first. I solved this by taking my time changing one column at a time. Eventually once my graph matched with the example in the instructions I knew I completed the task correctly. 

## Results

	When observing the pivot table/graph from the Outcomes based on Launch Date worksheet, we can conclude that summer months 
  such as May and June had the most successful campaign run. The month of December has almost as many failed campaigns as successful. This visual shows us a pattern of summer months that Louise can use to determine a safe start date for another campaign. For the Outcomes based on Goals, it is easy to conclude that campaigns with smaller goals have a greater success rate of meeting those goals. There was an exceptionally high fail rate for projects over the goal of 45000 which we can observe on the line graph. The success rate almost stayed in a constant decline as the goal got larger. This dataset could have limitations based on time constraint. If Louise is trying to determine the best month to launch a new campaign, it might be worthwhile to access multiple years of data like one of the other worksheets has and compare similar months than just viewing one year of data. The outcomes based on goals fails to prove any data for the "# canceled" column and does not include those campaigns that are currently live, which I think would be interesting to observe. We could also potentially compare launch dates to deadlines and how long successful campaigns tend to last with a line graph.
