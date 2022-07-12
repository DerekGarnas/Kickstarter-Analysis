# Crowdfunding Analysis Using Microsoft Excel

## Overview of Project
    This project focused on utilizing Microsoft Excel to analyze a data set depicting crowdfunding successes and failures on the crowdfunding platform known as "Kickstarter".


## Purpose
    The purpose of this project was to help a playwrite named Louise utilize available data regarding crowdfunding projects on the platform known as "Kickstarter".  Using Microsoft Excel to conduct various types of analysis and generate visual aids, we intend to help Louise optimize her crowdfunding campaign so that she has the best chance possible of garnering the financial resources she needs to fund her upcoming play, "Fever." 

## Analysis and Challenges
    We utilized numerous lines of code throughout the construction of this document to organize the data and extract useful information for our client, Louise.

    This included basic calculations like the mean.

    ![Calculating Mean](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Calculating%20Mean.jpg)

    We also calculated the median.
    
    ![Calculating Median](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Calculating%20Median.jpg)

    We calculated Standard Deviation.
    
    ![Calculating Standard Deviation Formula](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Calculating%20Standard%20Deviation%20Formula.jpg)

    We determined the percentages of successful/Failed/Canceled campaigns.
    
    ![Calculating percentage Successful_Canceled_Failed]9https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Calculati8ng%20percentage%20Successful_Canceled_Failed.jpg)

    We had to convert the dates included in our data set to something that was recognizable.
    
    ![Date Conversion Formula](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Date%20Conversion%20Formula.jpg)

    We used a different formula to extract the years each campaign took place.

    ![Extracting Years Formula](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/Extracting%20Years%20Formula.jpg)

    We used a command called COUNTIFS in order to narrow down the specific campaigns that we needed for comparison.

    ![COUNTIFS formula](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Screenshots%20of%20Formulas/COUNTIFS%20formula.jpg)

    During the course of our analysis, I ran into many challenges.  Virtually all of these aforementioned formulas were unknown to me prior to this assignment.  It is possible if not likely that one will enter a formula incorrectly when they are new to this program.  One particularly tricky formula to work with was the "COUNTIFS" formula that narrowed our search by a number of different criteria.

### Analysis of Outcomes Based on Launch Date

    ![Theater_Outcomes_vs_Launch](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png
    

### Analysis of Outcomes Based on Goals

    ![Outcomes_vs_Goals](https://github.com/DerekGarnas/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

    Over the course of this project, I encountered numerous challenges.  For one, I have never utilized Microsoft Excel for such advanced analyses and calculations, making it difficult to complete the required steps in our guide.  In addition, Microsoft Excel is quite particular about one's input and analysis of data.  Meaning, I could be completing the requisite task as outlined in our project guide, and then be held up with error messages for small oversights or mistaken entries.  I do not find this program to be as user-friendly as one would hope.
    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    Based on our analysis of campaign outcomes and the date at which they are launched is that the time of year one launches their campaign is significant.  Based on the graph we generated, it is apparent that the best possible month for one to begin their campaign is May.  Following May, it is apparent that the likelihood of success is on a gradual decline (overall), as it drops from June to December.  December is the "worst" month to launch one's campaign, perhaps because people (and their money) are focused on the holidays that take place during that time of year.  We see that there is an overall increase in the likelihood of success from the start of the new year, (January), until it peaks in May.


- What can you conclude about the Outcomes based on Goals?
    
    Based on our analysis, we can see that Louise has a good chance of raising the money she needs, (quoted as $10,000), if she can cut her costs a bit, and attempt to raise something in the range of $5,000 to $9,999.  If she cannot cut her cost of production, her next best shot at successfully raising the money she needs is to create a campaign meant to raise between $35,000 and $44,999.  It appears that campaigns falling within the range of $10,000 and $30,000 are far less likely to be successful, as the percent of successes drop off, while the percent of failures rises.

- What are some limitations of this dataset?

    There are a number of limitations inherent in this data set.  For one, it only covers campaign outcomes over a relatively small window of time.  The other limitation that is most readily recognized is that it only contains data from a handful of countries, leaving out data from other parts of the world.

- What are some other possible tables and/or graphs that we could create?

    We could have analyzed the lengths of campaigns and their outcomes to see if successful campaigns typically last a certain amount of time.  This is important information for someone using Kickstarter because when you create a new campaign you must set your own deadline.

    We could take the analysis of campaign lengths a step further by incorporating goal amounts and campaign outcomes.  By combining the information in each of these categories, one could determine how long a campaign must run in ordrer to successfully raise a particular sum of money.