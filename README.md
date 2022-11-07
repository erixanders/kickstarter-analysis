# Kickstarting with Excel

## Overview of Project
Analyzing and visualizing Kickstarter for Louise. Louise is interested in the outcomes of theatre play Kickstarters and how successful their campaigns were.

### Purpose
Give Louise an idea of how successful theatre play campaigns are on Kickstarter, as well as give an idea of what goals are most and least successful.

## Analysis and Challenges
Based on the data, it seems that people are feeling most generous around early summer, as May and June had the most succesful campaigns with 111 and 100 respectively, with July closing in closely with 87. 
![image](https://user-images.githubusercontent.com/3924733/200412651-1666f2cb-3fa5-4030-aacc-0aff8e262ae2.png)
For campaign goals, it would seem that campaigns with a goal of 19,999 and less all have a chance of success of 50% or above, so starting from there and going down will more than likely get you funded.
![image](https://user-images.githubusercontent.com/3924733/200413124-9f864631-ce6d-4cd1-9dbd-9adcc7bc489e.png)

The biggest challenge was having some things feel meticulous in Excel without a clear way how to automate it. For example, having to manually type in a lot of things for the Outcomes Based on Goal sheet got annoying. Copy and pasted to the best of my ability, but had to manual change formulas quite a bit due to how unique they are.

### Analysis of Outcomes Based on Launch Date
This one wasn't too hard, creating a pivot table is more on the automated side of things and the chart is easy to create as well.

### Analysis of Outcomes Based on Goals
This one was a bit tougher, the "countifs" jumbled my brain a bit, but once I got used to it it seemed to breeze by, but was still a bit meticulous

### Challenges and Difficulties Encountered

Listed this in the "challenges" already.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
May is the best time to launch a Kickstart, with a near 67% of projects in that time getting funded. 
The fall seasons(Oct-Dec) seem to be some of the worst time, October alone has a nearly 44% fail rate. People are more than likely saving for the coming holidays rather than funding other things.

- What can you conclude about the Outcomes based on Goals?
For campaign goals, it would seem that campaigns with a goal of 19,999 and less all have a chance of success of 50% or above, so starting from there and going down will more than likely get you funded. For plays it seems that having too lofty of a goal means greater chance of failer in some cases, however 35,000-44,999 had at 67% success rate each, so it's not impossible.

- What are some limitations of this dataset?
Doesn't list individual pledges, marketing budgets,and by as well as who is starting it which could have huge implications on the success of a campaign

- What are some other possible tables and/or graphs that we could create?
Box and Whisker to see the outliers for these so you can determine what is the safest goal to set.
