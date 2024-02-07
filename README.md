# Project_1_Team_5

Project Title: Health Outcomes Across States: Evaluating the Impact of Insurance and Preventative Care

Goal: Our project aims to show the impact of health insurance on receiving care and overall health outcomes at the state level for the years of 2018-2019.

Relation to Healthcare Industry:
Premature mortality can explain relationship between the health and wealth of nations, healthcare accounts for 10 percent of gross domestic product (GDP) of most developed nations. 
In a well-functioning health system, premature deaths (under the age of 75 years) can often be avoided through public health interventions and quality medical care. Our focus is on whether health insurance acts as a gateway to preventative care services that reduce premature mortality.

Questions to answer: 
1. Is there a correlation between the percentage of uninsured adults and premature mortality rates per state? 
2. Which has more influence on health outcomes, not having insurance or not having a primary care provider? 
3. What are the Top and Worst 5 state rankings?

Data Collection: 
Datasets used: https://github.com/redpandata19/Project_1_Team_5/tree/main/Resources
Our Source: The Commonwealth Fund 
Data collected from: CDC National Vital Statistics System (NVSS)
https://www.commonwealthfund.org/datacenter/uninsured-adults?performance_area=9366
https://www.commonwealthfund.org/datacenter/adults-usual-source-care
https://www.commonwealthfund.org/datacenter/premature-avoidable-deaths-100000-population?performance_area=9371
https://www.commonwealthfund.org/datacenter/premature-deaths-preventable-causes-100000-population?performance_area=9371
https://www.commonwealthfund.org/datacenter/premature-deaths-treatable-causes-100000-population?performance_area=9371


Data Cleanup: 
https://github.com/redpandata19/Project_1_Team_5/blob/main/Data_Cleanup.ipynb

Data Analysis: 
https://github.com/redpandata19/Project_1_Team_5/blob/main/Data_Analysis.ipynb

Presentation: 
https://github.com/redpandata19/Project_1_Team_5/blob/main/Project_1_Team_5_FC.pptx

Conclusion:
1. Lower percentage of uninsured adults correlated with fewer avoidable, treatable, and preventable deaths per state.
      Pearson’s correlation coefficient between 0.3 - 0.4. Moderate correlation for all data sets. 
2. Negative correlation (-0.69) between uninsured adults and not having a primary care provider
      Emphasizes the positive impact  of health insurance on seeking preventative medical care
3. Identified two states with trending positive healthcare outcomes, and three states trending negative healthcare outcomes.
      Best: Massachusetts, Minnesota | Worst: Mississippi, Oklahoma, West Virginia
      Starting point for expansion into different factors influencing the states positive or negative healthcare outcomes

Limitations
-The analysis is based on data from 2018-2019, which represents a relatively short time frame and does not include trend analysis over time. 
-Does not reflect changes since covid pandemic.
-Having a primary care provider does not equal regular doctor visits
-The uninsured correlations only included adults, not uninsured children


The correlations did not include uninsured children.

What would we do differently?  
-Combined the children and adults data sets for uninsured and compared adult-only, child-only, and the combination.
-Limit the premature death factor to 1 data set and instead explored additional factors.








