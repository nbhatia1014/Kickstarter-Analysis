# An Analysis of Kickstarter Campaigns.

## Overview of Project

### Purpose
The purpose of the project was to help Louise analyze how different kickstarter campaigns fared in relation to their launch dates and fundraising goals. For this analysis, we studied 4,113 kickstarter campaigns that varied in categories, goals, pledges, outcomes, and other characteristics. We used Excel tools such as Pivot Tables, Pivot Charts, and Excel functions such as CountIfs to create vizualizations to help Louise analyze outcomes based on goals and outcomes based on launch date.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![This is an image](https://github.com/nbhatia1014/Kickstarter-Analysis/blob/1b56bb1a9f87cb1bdd37f2a32ed66b8a1b34d978/Module%201%20Resources/Theater_Outcomes_vs_Launch.png)

In the above analysis we used Pivot Tables and Pivot Charts to help Louise visualize the relationship between outcomes and launch month. In order to make the data more relevant to Louise's fundraiser, we filtered the pivot tables by Parent Category and by the Years in which the fundraisers were started. We used the "Convert Text to Columns Wizard" so we could seperate the Parent / Subcategory column into a Parent and a Subcategory column. This allowed us to filter by only the Parent Category and we were able to filter to Theatre to make the data more specific to Louise's fundraiser. In addition, we filtered our pivot table to exclude the "Live" fundraisers so we were able to narrow down the data so we could analyze just the completed fundraisers. 

### Analysis of Outcomes Based on Goals
![This is an image](https://github.com/nbhatia1014/Kickstarter-Analysis/blob/f1b0115bc1b5bb709e6909636bf9574f82d5fe80/Module%201%20Resources/Outcomes_vs_Goals.png)

In the above analysis we used the CountIfs function and line charts to help Louise visualize the percentage of successful, failed, and canceled plays based on the fundraising goal amount. In order to make the data more relevant, we used a four criteria CountIfs() function to help classify the data by 12 goal ranges, by the "Play" Sub Category, and whether the campaign was Successful, Failed or Canceled. 

### Challenges and Difficulties Encountered

I found that the Outcomes Based on Launch Date analysis was easy to understand and fairly straight forward to create. The issues that I could see being ecountered come from the Year() function. Had this step been forgotten, the Pivot Table Filters may have been difficult to create.

During the Outcome Based on Goals analysis I had an issue with the multi criteria CountIfs() function. In addition, it was very tedious to create the functions for all 36 entrires that were needed. To overcome this issue, I used the the F4 item to lock the columns on the Kickstarter data page. Then I dragged the function to the various Successful columns. After I finished the Successful column, I dragged the forumulas over to the Failed and Canceled columns and used the find and replace tool to update the Criteria to be either Failed or Cancelled. 

## Results

After reviewing the Outcomes based on Launch Date chart, I was able to come to two important conclusions: (i) Using Kickstarter to fundraise for a Theater project are more likely to succeed than to fail and (ii) The most popular and most successful quarters to fundraise are in 2Q and 3Q (April - September).

  (i) After reviewing the data in the Pivot Table, Theater fundraisers succeeded ~61% of the time and failed ~36% of the time. Only 3% of the fundraisers were canceled. This signifies that nearly 6 out of every 10 theatre fundraisers will be successfull. This should be reassuring to Louise in her quest to fundraise for her Theater project. She is far more likely to succeed in her fundraising goals.
  
  (ii)
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
