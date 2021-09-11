# Kickstarting with Excel

![Picture of Theater](https://worldoftheatreandart.com/wp-content/uploads/2014/06/Theatre-paly.jpg)

## **Overview of Project**

###  *Purpose* 
        
Experiences are what make life meaningful. Whether it be with a loved one or independently, we as social beings 
are drawn to events and moments that live in our memories forever. Such meaningful moments exist in our every day lives 
and through the artistic endeavors we explore. The theater is one of those magical places. However, what few fail to 
recognize when walking into a play or musical is the volume of blood, sweat, and tears that is required to lift an idea 
off paper and into a fully funded and well executed production that leaves an audience awestruck and imprinted on one's 
memory forever. 

The purpose of this project is to better understand the first step in this critical process. What are the essential ingredients that leads to a terrific recipe that can be made over and over again? Through a deep analysis of Kickstarter campaign data, the essential ingredients will become more clear. Does launch date, number of backers, or funding goals, or other critical metrics impact whether or not a campaign is fully funded and therefore successful? 

## **Analysis and Challenges**

In an effort to better understand what makes a campaign fully funded and successful, data was extracted from the Kickstarter website and then sorted to isolate a few key metrics:
  - outcomes - was a campaign successful or not?
  - goal - how much was identified as the necessary amount needed to make the project come alive?
  - parent and sub categories - how were projects identified within the world of performing arts?

First, simple color-coding was conducted to visually identify campaigns that were successful (green), failed (red), were canceled (yellow), or that are currently live (blue). After identifying these results, a comparison was completed to determine if there was a difference in goal amount set for the project and if that goal amount was actually met by reviewing how much was pledged to the campaign. Through these steps, and some data manipulation, a clear question began to emerge: It is not only important if a campaign is successful, but does when the campaign occur impact the project from going from an idea to the stage?

### *Analysis of Outcomes Based on Launch Date*

The first deep dive into this larger question "What are the essential ingredients that leads to a successful campaign?" focused on the outcome of the campaign based on the launch date. Specifically, when are campaigns typically successful in meeting their goal? This data is illustrated below.
  
  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/87885677/132959247-dac5f1ab-d207-400b-9ac3-61e4d328ff09.png)
   
   
### *Analysis of Outcomes Based on Goals*

Digging a bit further into what makes a successful campaign, it's also critical to sift through the monetary impact of successful campaigns. Is a campaign successful when the goal is lower versus if the goal is higher? This data is illustrated below.
      
      
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/87885677/132959321-cea80bbc-d5ef-4435-a2bf-e04c136d229a.png)
        
        
### *Challenges and Difficulties Encountered*

In working with this Kickstarter data set there were no immediate challenges that became present in this analysis. With that possible chllaenges that could arise in further analysis of this data set could include how campaigns are defined (i.e. categories and sub-categories) which could have a larger influence in the ability to clearly determine what are the essential ingredients in making a successful campaign. 

## **Results**

### *Conclusions*

By throughly reviewing this data two clear message emerged. First, the best time to launch a campaign is summer. Based on analysis of the [launch date data], the number of campaigns is higher and the number of successful campaigns compard to failed is significant during the summer months (i.e. May, June, and July). As campaigns transition out of the summer window and into the fall, there is a drastic shift in successful versus failed campaigns with there being almost no difference in successful and failed campaigns.
    
A second conclusion drawn from the data is focused on monetary impact, specifically, the lower a goal is for a campaign the higher the chance it will go from paper to the main stage. Keeping goals smaller could make it easier for backers to pledge and therefore the goal is hit more often than not. Campaigns that set a goal of less than $5,000 have a ~70% success rate compared to campaigns that set a goal between $5,000 and $20,000, which result in a ~50% success rate. 

### *Limitations*

As noted earlier in this analysis, one of the limiting factors that could have an impact on this data set is how categories and sub categories are identified and defined by Kickstarter. Are these self-identified by the organizer of the campaign or does Kickstarter have some control over these labels? This could impact how the data is viewed compared to other campaigns and potential organizers. 
    
Additionally, the current Kickstarter data set spans from 2009 (the inception of Kickstarter) to 2017. With that we are currently missing the last 4 years of Kickstarter data. Much has happened in this time, especially to the performing arts world that could greatly impact the success of a campaign. During this time, the world has been engulfed in an international pandemic  which has closed many performing arts establishments and have led to lay offs of many staff and performers. Returning to pre-COVID numbers may look very different. 
    
Finally, there are more specific elements of the data set that could impact the Kickstarter analysis. For example, what are the age ranges of the donors for successful campaigns? What is the average income of donors within those age ranges? Does reputation of an organizer or performer impact a campaigns ability to be successful? Many of these questions deserve further analysis and are not included in this report.

### *Additional Tables and Graphs*

There are additional tables and graphs that could present the data in a different light, which could lead to further conclusions in creating the right recipe for success. For example, review of data based on annual results each year instead of monthly could more so reflect the state of the economy and backers willingness to give more or less during particular windows. Additionally, reviewing average donations by campaign outcome, data based on staff pick, or digging deeper into data specific to countries could all tell a different story about how a campaign could rise to success.

