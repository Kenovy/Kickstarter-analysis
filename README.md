# Kickstarting with Excel

## Overview of Project

### Purpose

This project was intended to help our customer to understand how fared their campaigns were in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/Kenovy/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/Kenovy/Kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
The only challenge I experienced was with the COUNTIFS() function and it was related to a mistake from my end, mixing the formula and writing incorrectly the value <=, using instead =< which caused me Excel return a value 0 as resulted. 
## Results

*- What are two conclusions you can draw about the Outcomes based on Launch Date?*

**1-** As a result of the analysis, it is notable that over the years during Q2 and Q3 is when we have the most successful theater campaigns and it´s the period where more campaigns are launched as well.

**2-** The analysis told us that over October there is a slight increase in campaigns but they have not been as successful compared to those launched in Q2 and Q3. It means, that the best stage to launch campaings is on Q2 and Q3. 

*- What can you conclude about the Outcomes based on Goals?*
What the analysis shows us is that although we have a higher percentage of successful campaigns, we have a similar trend between successful and unsuccessful campaigns but in differente opposite, which suggests that we need to reconsider the goal pledged for these campaigns, specfically over the last Q4 of the year.

*- What are some limitations of this dataset?*
I think the only limitation of this dataset was that the category and sucategory were in a single column, but it was fixed easily using the "Text to Column" function within excel. 

*- What are some other possible tables and/or graphs that we could create?*

**Theater Outcomes by Launch** Clustered column could be an additional option to use. 

![Theater_Outcomes_vs_Launch_AdditionalOption](https://github.com/Kenovy/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch_AdditionalOption.png)

**Outcomes_vs_Goals** A PivotTable could be a good option to process, sort and read the data easily 

![Outcomes_vs_Goals_AdditionalOption](https://github.com/Kenovy/Kickstarter-analysis/blob/main/Outcomes_vs_Goals_AdditionalOption.png)

