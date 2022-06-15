# kickstarter-analysis[ Kickstarter_Challenge.md](https://github.com/samboest/kickstarter-analysis/files/8913571/Kickstarter_Challenge.md)
# Kickstarting with Excel

## Overview of Project
This projects provides an oppertunity to test key excel formulas and functions.  Students were asked to review fundrasing data, with the goal of comparing campaigns types, funding goals and launch dates. 
### Purpose
The true purpose of this assignment is to make a business decision to improve the outcomes of future campaigns. A few example questions are:

- Which campaign  succeeded? 
- Is there any relationship to launch dates or size of the campaign?
- Where should we focus our attention and labor?

Those are the types of questions, I would be asking of this team.

## Analysis and Challenges
Reviewing the analysis, it appears we are starting high-level to review parent category launch dates.  I would think of this as a simple review of seasonality for a category or business unit.  The overall success of the play *Fever* should have some relationship to the success of the the parent category "theater". Upon graphing launch dates the ideal *Launch Months* were easily visualized. After understanding the best timing, we drilled down further to review the subcategory of "plays". In this analysis we focused our attention to understand the succcess rates related to goal amounts.  Looking at these results we are then prepared to compare our findings to the data we have on *Fever*.

### Analysis of Outcomes Based on Launch Date
From 2009 to 2017 the number of campaigns increases significantly during late spring and through the summer.  The months of May and Jun had the highests success rates of any month. The *Fever* campaign started in July.  With this information, we could consider caimpaigning for this play in during those months.   

### Analysis of Outcomes Based on Goals
The *Fever* campaign had a very small fundraising goal.  The campaign failed with a pledged to goal percentage of 86%.  This is still pretty high and is probably the reason why we are revisiting this campaign.  Placing the goals into ranged buckets, we were able to view preformance across the size of the campaigns. The campaigns with the highest success rates all have a budget under $10,000.

### Challenges and Difficulties Encountered
While using countif functions, I did not add the subcategory "plays" as a condition. Other than that oversight, I had no problems with the excercise. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. We could conclude that the majority of theater caimpaigns do succeed.  
    2. Looking at the unfiltered chart, we could conclude and recommend pushing the start date back into May or Jun. While not uniform year to year, we do see somewhat of a similar pattern when we drill down to individual years
    3. We could also conclude not to ever run campaigns in December. 

- What can you conclude about the Outcomes based on Goals?
    1. The *Fever* campaign size is in a high success range.  I would recommend not changing the size of the campaign.  
        Someone could argue that less than 1000 is ideal, but is a 3% increase justification to lower the budget.  I'd argue it is not. 
- What are some limitations of this dataset?
    This dataset has limited data beyond 2014.  I would not use this data set to forecast longterm trends or make broad statments about a category or business unless I was already familiar with that business.  we have campaign names, but im assuming these are marketing projects with creative.  I'd like to learn about the campaign type such as, "mailer". "email", "influernce".  Adding texture like this should improve decision making. 

- What are some other possible tables and/or graphs that we could create?
    We could look at a trend line for when the most money is pledged.  We looked at goal amount, but looking at pledged dollars may be a better way to make a decision. 
