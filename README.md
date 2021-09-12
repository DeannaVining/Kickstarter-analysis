# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

## Overview of the project
This project is meant to uncover trends in the success level of various projects Kickstarter, based on the time that the funding started and the goal amount. The intent with this information is to help guide Louise in her endeavor to look at the trends of the other campaigns in comparsion to her play Fever.

## Analysis and Challenges
The analysis started by looking at trend of the theater campaigns in the Kickstarter data. This was accomplished by creating a pivot table and line chart of the amount of successes, failures, and cancellations of the various plays by month. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/87716330/133005933-80391064-d03c-4e92-ba0f-f9c4aa9aca7c.png)



Once the theater category had been broken down by the month launched, the focus turned towards an overall look at the percentage of successes, failures, and cancellations of projects based on the goal amount. The goal amounts were broken down in general by increments of $5000, as can be seen in the image below. This image is a line chart, depicting the percentage of the outcomes.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/87716330/133006094-31b397af-4052-4db6-8ca1-53d34958f158.png)



## Results
 Two conclusions made from the Theater Outcomes By Start Date are:
  
  1) The months from May to August produced the most amount of successful theater campaigns.
  2) The amount of canceled and failed campaigns minimally changed from month to month.


Conclusion made from the Outcome Based on Goals:
  1) The percent of successes is significantly higher in campaigns that had larger initial goal amounts (over $1000).
  2) Thus, the percent of failure is significantly higher in the campaigns that had an initial goal of less that $1000.


Limitations of the data set: 
  1) There is not a uniform number of kickstarters starting theater projects every month.
  2) No data column for the timeframe in which the campaigns were collecting money (though this could be calculated).


Other possibilities to help create an analysis:
  1) Create a chart with percentages for the outcomes by start date.
  2) Create a chart with outcome percentages, based only on the theater category.
  3) If the time of year and goal for funding for the particular play of note, Fever, were known, we could then create some tables based on that subset of the data.
