# Kickstarting with Excel

## Overview of Project

### Purpose 
### _**This kickstarter analysis is to provide an understanding of the fundraising goals and outcomes and how different campaings faired in relation to launch dates and funding goals. Below you will find some visualizations of campaign outcomes based on their launch dates and their funding goals.**_ 
---
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![theater_outcomes_vs_launch](https://github.com/hastyjr/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![outcomes_vs_goals](https://github.com/hastyjr/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
One of the biggest challenges and difficulties I had was getting this chart to read outcomes accordingly. Not matter how I wrote the formula, my outcome was 0 for the data sets of 40000 to 49999, even when there were kickstarters within this range. Screenshots of the formulas below, and the disparity between those numbers and the rest. 
![challenges_screenshot_1](https://github.com/hastyjr/kickstarter-analysis/blob/main/Resources/Screen%20Shot%202022-06-15%20at%2000.07.46.png)

![challenges_screenshot_1](https://github.com/hastyjr/kickstarter-analysis/blob/main/Resources/Screen%20Shot%202022-06-15%20at%2000.14.35.png)

---

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**

    Conclusions I can draw about the Outcomes based on Launch date are:
        
    The data shows that leading up to the month of May (across all years) is when most fundraising kickstarters are created or kicked-off. The second peak of kick-offs are in February, which aligns to early year planning for getting fundraisers off the ground and launched. 
        
    We can also conclude that statistically fewer kickstarters are successful early on in the year. They gain steam leading up to May. The data also shows that if the kickstarter hasn't started by May that the chances of getting it launched decreases and the probability of the kickstarter almost equally increases on the failed side. 

- **What can you conclude about the Outcomes based on Goals?**

    I have drawn to the conclusion, despite my challenges, that the larger the goal, the smaller the chance of success. You would think it would opposite, in that the smaller the goal the better chance of success and the higher chance of failure.

    When it came to the smaller goals, success is still most likely, but and proves that as the goal rises, the chance of success lowers and failure rises. 
    

- **What are some limitations of this dataset?**

    The limitations of the dataset here is that we're calculating multiple sets of currency and they don't translate to the correct rate. 

    At this point in the analysis, we have not compared `Date Created` and `Date Ended` with the actual `Due Date`. So while there might have been success, it could have also taken a substantial amount of time to meet the deadline. 

- **What are some other possible tables and/or graphs that we could create?**

    Some other possible tables / or graphs we could create are those like I stated above in the limitations of the dataset. Creating a graph of Kickstarted total time to goal completion in comparsion to the due date. It would have also been beneficial to see this broken down by country and accurate currency comparison in terms of percentages.        
