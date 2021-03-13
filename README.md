# Kickstarting with Excel

## Visualizing kickstarter campaign outcomes based on their launch dates and their funding goals

### Purpose
The objective was to give Louise the ability to compare her kickstarter campaign results with the rest of the plays. This would be performed by isolating the theater launch date, outcomes and goal data so that Louise could determine where she stands.

## Analysis and Challenges
The analysis was performed by using kickstarter campaign data which included the necessary information related to launch dates and funding goals based on outcomes. Further, the data included data such as: Date created, date ended, goal amounts, pledge amounts, parent category and subcategory, and campaign outcomes. Some of the challenges included not being able to vet the information and perform further analysis for Louise.

The Excel file that shows the analysis is located here: [GitHub Pages](https://github.com/trallen09/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
### Analysis of Outcomes Based on Launch Date
Using parent category, outcomes, and date created, I was able to determine the best launch date specific to theater campaigns. Filtering on the parent category "theater", I summarized a pivot table based on launch date for rows and outcomes for both columns and count of outcomes.  

![alt text](https://github.com/trallen09/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
The use of COUNTIFS allowed me to set the criteria for plays, goal limits, and outcomes. I had to create different limits to capture outcomes based on goals that fell between 1000 to 50000 within the COUNTIFS function. All the data was filtered for plays.

![alt text](https://github.com/trallen09/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
Some of the challenges and difficulties were associated with not being able to compare Louise's play with other similar plays. There could have been more data to further categorize the type of plays. Also, we could have created other charts and graphs to do more of an apples to apples comparison such as duration of campaign within plays. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Campaigns have the best chance to succeed in May. Failures and canceled campaigns are consistent throughout the year with October being the highest failures.
- What can you conclude about the Outcomes based on Goals?
  - The most successful campaigns are under $10,000 while most campaigns over $45,000 tend to fail. Over 80% of the campaigns are under $10,000 as well.
- What are some limitations of this dataset?
  - There could be errors within the data since I did not search for duplicates and other cleaning proceedures.
- What are some other possible tables and/or graphs that we could create?
  - We could create a graph for outcomes based on year, outcomes based on category, and category based on goals. 
