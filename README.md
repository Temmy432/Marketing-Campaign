# Marketing-Campaign
This report evaluates marketing campaign performance using key metrics like ROI, CTR, CPC, and conversion rates. It analyzes channels, audience segments, and locations to optimize strategies. Insights and recommendations are backed by data visualization using Python, Pandas, and Seaborn.



TABLE OF CONTENTS:

INTRODUCTION

OBJECTIVES

DATA SOURCE

DATA OVERVIEW

METHODOLOGY

DATA PREPROCESSING

DATA ANALYSIS AND VISUALIZATION

KEY INSIGHTS

RECOMMENDATIONS

CONCLUSION

INTRODUCTION

This report provides an in-depth analysis of the performance metrics of recent marketing campaigns. By examining key indicators such as Campaign ID, Return on Investment (ROI), Click-Through Rate (CTR), Cost Per Click (CPC), and Conversion Rate, we assess effectiveness and identify areas for optimization.

The goal is to provide data-driven insights to enhance future strategies, audience engagement, and budget efficiency. Through visualization and trend analysis, this report highlights strengths and weaknesses, helping stakeholders make informed decisions.

OBJECTIVES

Optimize Channel Performance – Identify the most effective platforms for engagement and conversions.

Maximize Campaign ROI – Determine which strategies yield the highest profitability.

Enhance Location-Based Targeting – Optimize marketing efforts based on geographic insights.

Increase Audience Reach – Improve exposure by assessing total impressions by channel.

Boost Audience Engagement – Identify impactful content and messaging strategies.

Refine Target Audience Strategy – Personalize marketing efforts for better audience targeting.

DATA SOURCE

The dataset, "marketing_campaign_dataset.xlsx," was provided by HNG TECH and contains comprehensive marketing campaign data, including impressions, clicks, conversion rates, acquisition costs, and engagement metrics.

DATA OVERVIEW

The dataset consists of 200,005 rows and 15 columns, capturing key attributes such as:

Campaign – Name of the marketing campaign.

Company – Organization responsible for the campaign.

Campaign Type – Category of the campaign (e.g., social media, email, TV ads).

Target Audience – Demographics or behavioral patterns of the audience.

Duration – Campaign runtime.

Channel Used – Platform distributing the campaign (Facebook, Google Ads, etc.).

Conversion Rate – Percentage of users taking desired action.

Acquisition Cost – Cost incurred to acquire new customers.

ROI (Return on Investment) – Profitability measure.

Location – Geographic region where the campaign was executed.

Date – Campaign launch or milestone date.

Clicks – Number of interactions with the campaign.

Impressions – Number of times content was displayed.

Engagement Score – User interactions (likes, shares, comments).

Customer Segment – Classification of customers for personalized marketing.

TOOLS USED

Python – Primary programming language.

Pandas – Data manipulation.

Matplotlib & Seaborn – Data visualization.

Jupyter Notebook – Interactive analysis.

METHODOLOGY

Importing Libraries – Loading essential libraries for data processing.





![](Images/Screenshot%2025-02-22%20191431.png)





Loading and Exploring Data – Reading the dataset, checking structure.


![](Images/Screenshot%202025-02-22%20192423.png)


Data Cleaning – Handling missing values, correcting data types, removing duplicates.


 ![](Images/Screenshot%202025-02-22%20193804.png)                                                                      




![](Images/Screenshot%202025-02-22%20193741.png)                                                                




![](Images/Screenshot%202025-02-22%20193750.png)




Data Transformation – Converting data to appropriate formats.



![](Images/Screenshot%202025-02-22%20193659.png)



Descriptive Statistics – Summarizing key metrics like mean, median.


![](Images/Screenshot%202025-02-22%20193812.png)


Outlier Detection – Using the Interquartile Range (IQR) method.


![](Images/Screenshot%202025-02-23%20143716.png)


 ## DATA ANALYSIS AND VISUALIZATION

# PERFORMANCE METRIC CALCULATION

The key marketing metrics were calculated such as the Click Through Rate (CTR), Cost Per Click (CPC), and Return on Investment (ROI).



![](Images/Screenshot%202025-02-23%20150455.png)



# AVERAGE METRICS BY CHANNEL USED



![](Images/Screenshot%202025-02-24%20133455.png)




# INSIGHTS

CPC is high across all channels.

Engagement with ads remains stable regardless of the platform used.

ROI is the lowest metric.

YouTube shows high CPC but relatively lower conversions.

# TOTAL ROI BY CAMPAIGN TYPE



![](Images/Screenshot%202025-02-24%20135207.png)




# INSIGHTS

Influencer campaigns have the highest ROI.

Social media campaigns have the lowest ROI.

ROI fluctuates across different campaign types.

# TOTAL ROI BY LOCATION



![](Images/Screenshot%202025-02-24%20135550.png)



# INSIGHTS

Miami generated the highest ROI, slightly surpassing other locations.

All locations have similar ROI percentages.

New York and Houston had the lowest ROI.

# TOTAL IMPRESSIONS BY CHANNEL USED


![](Images/Images/channelused.jpeg)



# INSIGHTS

Google Ads has the highest impressions, followed closely by Email.

Facebook has the lowest impressions.

The distribution of impressions is relatively even across all channels.

Cumulative Engagement

# INSIGHTS

Search campaigns had the highest engagement, followed closely by Influencer marketing.

Display ads and email campaigns performed moderately well.

Social media had the lowest engagement.

Average Engagement Level by Audience

Insights

Men aged 18-24 have the highest engagement score.

Women aged 25-34 also show strong engagement.

Women aged 35-44 have the lowest engagement, though differences are minimal.

KEY INSIGHTS

Google Ads, Email, and Website generate the highest impressions, making them key awareness drivers.

Search and Influencer campaigns achieve the highest engagement.

Men aged 18-24 and Women aged 25-34 engage the most.

Social Media has lower engagement despite high usage.

Miami has the highest ROI, indicating a strong market potential.

Location-based ROI varies, emphasizing the need for region-specific strategies.

Influencer marketing is crucial for audience participation.

Better targeting and content optimization are needed across all channels.

RECOMMENDATIONS

Prioritize Google Ads, Email, and Website for awareness, while improving social media engagement strategies.

Invest more in Search and Influencer campaigns for higher audience connection.

Focus on Men 18-24 and Women 25-34, tailoring content to their preferences.

Reallocate budget based on location-specific ROI, scaling efforts in high-performing regions.

Improve social media strategies by enhancing content quality and targeting.

Leverage influencer marketing in high-ROI regions to boost conversions.

Personalize website and email campaigns to convert high impressions into sales.

Continuously analyze and refine strategies for sustained marketing growth.

CONCLUSION

The analysis highlights that Google Ads, Email, and Website generate the most impressions, while Search and Influencer campaigns drive the highest engagement. Younger male (18-24) and female (25-34) audiences exhibit the strongest engagement, making them priority targets. Despite its reach, Social Media shows lower engagement, suggesting a need for strategic refinement. Miami has the highest ROI, yet marketing efforts there do not fully align with its performance, presenting an opportunity to maximize investment. Location-based ROI varies significantly, emphasizing the importance of tailored regional strategies. Optimizing underperforming channels and leveraging high-engagement platforms will enhance marketing efficiency and profitability.


