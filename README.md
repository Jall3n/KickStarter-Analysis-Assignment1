# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of the assignment is to utilize the skills we learned in excel to help Louise find out more information about the campaign goals of other theater plays. Additionally, we want to present a story using visualization methods based on the kickstarter data provided through line charts.  
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/119149740/209416901-e168ac74-73ef-4d50-83ab-c0d4e3d39432.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/119149740/209416985-a7eb019a-fb1f-4580-a1ae-178a86a90fd4.png)

### Challenges and Difficulties Encountered
- The first challenge that I encountered invovled splitting out the date conversion into months on the pivot table. However, found out I can right click on the date in the pivot table and group it into month instead of year and day. 
- The second challenge involved setting up the countifs statement, but found out I needed to adjust my initial formula. My error was stemming from the goal dollar amount range in the formula. I had to add criterias for the ranges such as ">=1000" and "<=4999"

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. Summer, especially May through July, has a higher number of successful outcomes compared to Winter
  2. Even though the month of December was close, overall, there were more successful outcomes for every month

- What can you conclude about the Outcomes based on Goals?
  Campaign goals that were less than 15,000 were more successful. However, except for a small number of outcomes within the 35,000 to 45,000 range the higher in goal amount the more likely you were to fail.

- What are some limitations of this dataset?
  - Certain countries may have more resources compared to others
  - The amount of interest in a country to watch a play
  - The actors and actresses' ability to perform and their status/recognition
  - The venue and marketability of the play

- What are some other possible tables and/or graphs that we could create?
  - A table or graph of the amount pledged for successful/failed campaigns compared to the goal amounts
  - Can compare the number of backers with the dollar amounts pledged 
  - Can use year instead of month for the Theater Outcomes
  - Can breakout outcomes by country
