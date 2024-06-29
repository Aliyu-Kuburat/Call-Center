# Call-Center

## Table of contents

- [Introduction](#Introduction)
- [Insights](#Insights)
- [Data Soures](#data-sources)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


### Introduction
This is a multi-feature dataset for customer records associated with a European Telecom Company Dataset. It deals with when customers call in, how long it took before, during, and after the call, and the resolutions given for the problems they called in for. The sample data is structured in rows and columns, and saved in a .csv file.

Key Features include: id, customer_name, sentiment, csat_score, call_timestamp, call_day, reason, city, state, channel, response_time, call duration in minutes, call_center

### Insights
<img width="739" alt="image" src="https://github.com/Aliyu-Kuburat/Call-Center/assets/156312358/10f0fa5a-0ce0-4eb9-bd7a-db758f82e300">

<img width="785" alt="image" src="https://github.com/Aliyu-Kuburat/Call-Center/assets/156312358/b2825477-dedb-4c20-984e-b0d26d8f69eb">





### Data Sources

Call Center data: The primary dataset used for this analysis is the "Call Center. cvs" file but was converted to an Excel file before analysis.

## Tools

- Excel
  I conducted a comprehensive analysis using only Excel, which included: data cleaning, formatting, exploration, statistical testing, analysis, and visualization.

### Exploratory Data Analysis
With the following questions, I can gain insights into customer behaviour, satisfaction levels, operational efficiency, and areas for improvement in service delivery. It's important to use visualization tools and statistical analyses to uncover patterns and trends in this data.

 - Individual customer identifier. Check for unique values to ensure data integrity.

 - Analyze customer names to identify frequent callers or patterns in customer interactions.

 - Explore sentiment data to understand overall customer feelings during calls. Identify trends in positive or negative sentiments to gauge customer satisfaction.

 - Evaluate customer satisfaction scores to determine overall satisfaction levels. Identify factors influencing high or low CSAT scores.

 - Analyze call timestamps to identify peak calling times. Optimize resources and staffing during high-volume periods.

 - Examine call distribution across days of the week. Identify trends or patterns related to specific days and adjust operations accordingly.

 - Categorize reasons for customer calls. Identify common issues or concerns to improve service and address recurring issues.

 - Analyze geographical data to identify areas with higher call volumes or specific regional trends. This can help in targeted service improvements.

 - Evaluate communication channels used by customers (e.g., phone, online chat). Identify preferred channels and optimize customer service delivery accordingly.

 - Analyze response times to understand how quickly customer queries are addressed. Identify areas for improvement in service efficiency.

 - Explore call duration data to identify average call lengths. Identify patterns in longer calls that may indicate complex issues or opportunities for efficiency.

 - Evaluate data based on different call centers to identify performance variations. Optimize resource allocation and training based on call center-specific insights.

### Data Analysis 
I used the Pivot table to analyse the data and charts to visualize.

### Results
## Created Dashboard
**Result:**
In October 2020, a total of 32,941 calls were recorded.

 - The predominant communication channel utilized by customers was phone calls known as Call center from the data.

 - The sentiment analysis revealed that calls with a negative sentiment were the most prevalent. Further investigation highlighted billing inquiries as the primary reason 
   for these negative sentiments. Additionally, billing questions also exhibited the highest levels of both negative and neutral sentiments compared to other reasons for 
   calling.

 - Regarding service level agreements (SLA), most calls (62%) were handled within the specified SLA timeframes. However, 24% of calls were addressed below SLA, 
   while 12% were handled above SLA standards.

 - The call center located in Los Angeles, CA, handled the highest volume of calls and received the highest proportion of very positive sentiments from callers.

 - In terms of states, California and Texas experienced the highest call volumes, with 3,631 and 3,572 calls, respectively.

 - The analysis indicated that on average, 2,174 customers made calls on 28-31 days per month.

 - Customer satisfaction scores (csat_score) predominantly fell within the range of 5 and 6, with a total of 1,899 and 1,865 customer reviews, respectively. Additionally, 
   568 customers rated their satisfaction levels at 9 or 10.

 - The busiest day for calls was Sunday, with the highest number of billing inquiries recorded at 76,774. Interestingly, the longest call durations were observed on 
   Tuesdays, coinciding with the peak volume of billing questions.
 - Thursday, Friday and Saturday have the highest number of billing questions from customers.


### Recommendations

Based on the analysis of the call center data, several recommendations can be made to improve overall performance and customer satisfaction:

1. **Focus on Addressing Billing Inquiries:**
   Given that billing inquiries are associated with the highest levels of negative sentiment and are the most common reason for calls, it's essential to prioritize 
   improvements in this area. Consider streamlining billing processes, providing clearer billing information to customers, and enhancing training for agents to effectively 
   handle billing inquiries.

2. **Optimize Response Time:**
   Analyze response time data to identify bottlenecks and areas for improvement in handling customer inquiries. Implement strategies to reduce 
   response times, such as optimizing staffing levels, implementing automated responses for common queries, and providing additional training for agents.
   
3.**Enhance SLA Compliance:**
   While the majority of calls are handled within SLA standards, there is room for improvement in addressing calls that fall below SLA requirements. Develop strategies to 
   improve SLA compliance, such as setting realistic SLA targets, monitoring performance closely, and providing incentives for meeting or exceeding SLA standards.

4. **Geographical Analysis:**
   Given the variation in call volumes and customer sentiments across different cities and states, conduct further analysis to understand regional trends and customer 
   preferences. Tailor customer service strategies and resources to meet the specific needs of customers in different geographic locations.

5. **Customer Feedback and Satisfaction:**
   Incorporate customer feedback mechanisms, such as surveys or feedback forms, to gather insights into individual customer experiences and satisfaction levels. Use this 
   feedback to identify areas for improvement and prioritize initiatives that address customer pain points.

### Limitations
 Based on the analysis of the call center data, several limitations can be identified:

1. **Limited Context:**
   The provided dataset offers insights into customer interactions and satisfaction levels, but it lacks context regarding the specific circumstances or details of 
   individual calls. Without additional context, it may be challenging to fully understand the reasons behind customer sentiments or issues.

2. **Data Completeness:**
   The dataset may have missing or incomplete data entries, which could impact the accuracy and reliability of the analysis. Missing data may lead to 
   biased conclusions or incomplete insights into call center performance.

4. **Single Dimension Analysis:**
    The analysis primarily focuses on quantitative metrics such as sentiment scores, CSAT scores, and response times. However, it may benefit from incorporating qualitative 
    data sources such as customer feedback or call transcripts to gain a more comprehensive understanding of customer experiences and satisfaction levels.

5. **Limited Scope:**
   The dataset covers a specific period and may not capture long-term trends or changes in customer behaviour over time. Additionally, it may not include data on 
   external factors such as market conditions, competitor activities, or changes in customer preferences that could influence call center performance.

6. **Generalization:** 
   While the analysis provides insights into overall trends and patterns, it may not account for variations in customer demographics, preferences, or needs. Generalizing 
   findings from the dataset to all customer segments or scenarios may overlook important nuances and differences among customers.

7. **Inability to Capture Real-Time Feedback:**
   The dataset likely represents historical data and may not capture real-time feedback or changes in customer sentiment. This limitation could hinder the call center's 
   ability to respond promptly to emerging issues or trends.

   Addressing these limitations may require supplementing the existing dataset with additional data sources, improving data collection processes, and incorporating more advanced analytical techniques to gain deeper insights into call center performance and customer satisfaction levels.




