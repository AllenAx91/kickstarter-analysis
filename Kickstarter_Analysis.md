# Kickstarting with Excel

## 1. Overview of Project
The Challenge "Kickstarter" is essentially a data analytics project which aims to provide the stakeholder, Louise, with actionable information that will enable her to plan a successful funding campaign.  The analysis in this report will assess the outcomes of past campaigns and the factors influencing campaign outcomes. In addition, limitations of the data provided will also be communicated through this report to aid Louise in drawing well-informed conclusions.

## 2. Purpose
  1) Providing Louise with tools that will replicate the success of past campaigns is the primary focus.
  2) To ascertain if Lousie's goal target of $10,000 is pragmatic

## 3. Analysis
The data set can be processed into multiple analysis projects that would help conlcude various factors involving the sucess and failure of a fundraising campaign. However, to serve the purpose of this project and to render a concise report, we are performing only two analyses. 

### 3.1. Challenges and Difficulties Encountered

To initiate our analysis, the data file had to undergo multiple levels of refining to arrive at the interpretable state it is in now. Some of the issues encountered are listed below:

 - Unix Date format - _Modified to short date format_
 - Category and Subcategory were merged - _Categories were split from subcategories using "Text to columns option"_
 - _Filtering options were enabled on the header_

On confirming that the data was readable, we performed some statistical analyses and then proceeded with a targeted analysis strategy as detailed in the remainder of this report.

### 3.2. Analysis of Outcomes Based on Launch Date

#### 3.2.1. Analysis through Data Visualization
For this analysis, a line chart was generated using excel to portray the influence of the launch date on the outcomes of various campaigns since 2015. The X-Axis and Y-Axis represent the "**Count of Outcomes**" and "**Months of the year**" respectively.
The representations of the coloured lines are as listed below:
 * Blue: Successful Campaigns
 * Orange: Failed Campaigns 
 * Grey: Cancelled Campaigns

![](https://github.com/AllenAx91/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

#### 3.2.2. Data interpretation

Although this chart provides a lot of information, the two points listed below stand out. 
 * _May has the most number of successfull campaigns_
 * _The graph also relveals that the count of failed outcomes in May are almost the same for the months of Jun, Jul, Aug and Oct_

### 3.3. Analysis of Outcomes Based on Goals

#### 3.3.1. Analysis through Data Visualization

To dwell deeper into the data and comprehend why certain plays were successful, another line chart was generated. This time, the X-Axis represents **ranges of goals** (roughly in 5000 increments) and the Y-Axis represents the **Outcome's percentage**. The three outcomes have are represented as lines as detailed below:
 * Blue: Successful Campaigns
 * Orange: Failed Campaigns 
 * Grey: Cancelled Campaigns

![](https://github.com/AllenAx91/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

#### 3.3.2. Data interpretation

Clearly, as the goals proceed to be extremely ambitious, the percentage of successful campaigns declines from **76%** in the range <1000 goals to **50%**in the range (15000 to 19999). 

## 4. Conclusion 

The month of May is probably the most successful because of the general outlook of the publicity in this season. It is during the spring that people are more than happy to indulge in leisure activities. This information will prove to be extremely useful for Louise's scheduling. One must also pay attention to the fact that the total number of campaigns in May is the highest of the year. This signifies that there is more to just launching a campaign in May. The competition is higher as more campaigns happen in the vicinity. Perhaps, a collaboration with other upcoming artists to hold joint campaigns can be considered. Also, It would be pragmatic for Louise to marginally mark down her initial campaign goal as the percentage of successful campaigns is significantly higher below the goal range of 10000 to 14999.

Attached with this report is also the excel file named ["Kickstarter_Challenge.xlsx"](https://github.com/AllenAx91/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx) that has been set up to help Louise derive more information.  

## 5. Limitations

The data is only a sample size as it was retrieved from a single website. Lousie will have to do a similar analysis based on data from other sources to validate the results explained in Section 4 "Conclusion" of this report. 

