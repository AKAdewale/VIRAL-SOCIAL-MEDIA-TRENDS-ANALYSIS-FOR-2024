📊 Social Media Analytics Dashboard – README
🧭 Outline
Introduction

Story of Data

Data Splitting and Preprocessing

Pre-Analysis

In-Analysis

Post-Analysis and Insights

Data Visualizations & Charts

Recommendations and Observations

Conclusion

References & Appendices

📌 Introduction
Objective of the Project
To analyze multi-platform social media performance data and identify content trends, platform engagement, and hashtag impact.

Problem Being Addressed
Brands and content creators struggle to understand which content types, hashtags, and platforms deliver the highest engagement. This project aims to answer that through data-driven insights.

Key Datasets and Methodologies
Dataset includes: Post_ID, Platform, Hashtag, Content_Type, Region, Views, Likes, Shares, Comments, and Engagement_Level.

Tools used: Microsoft Excel (Pivot Tables, Formulas), Charts, Conditional Formatting.

🧾 Story of Data
Data Source
The dataset was sourced from a social media management platform’s export feature.

Data Collection Process
Collected from post-performance APIs across YouTube, Instagram, TikTok, Twitter, etc.

Data Structure
Rows: Each represents a social media post

Columns: Variables like Platform, Views, Hashtag, etc.

Key Features
Views, Likes, Shares, Comments: Engagement metrics

Platform & Content_Type: Help identify channel and format trends

Hashtag: Indicator of trending topics

Data Limitations
Does not include user demographics

Lacks time-series elements (post time/date)

🛠 Data Splitting and Preprocessing
Dependent Variable: Engagement_Level

Independent Variables: Platform, Hashtag, Content_Type, Region, Views, etc.

Data Cleaning
Removed duplicates

Verified numeric columns

Standardized text values (e.g., lowercase hashtags)

Missing Values
Replaced blanks with 0 for numeric fields

Applied "unknown" for missing categories

Industry Context
Social Media & Digital Marketing

Stakeholders
Digital Marketers

Influencers

Brand Managers

Content Strategists

Industry Value
Optimizes content strategies, increases engagement, and improves ROI on campaigns.

🔍 Pre-Analysis
Key Trends
Top Engagement Platforms: YouTube (27.03%), TikTok (25.41%)

Content Types with Highest Likes: Posts, Reels, Tweets

Potential Correlations
More interactive content (Reels, Tweets) drives higher likes

Fitness and Education hashtags receive high engagement consistently

Initial Insights
Regional performance shows U.S., Canada, and U.K. as top regions by content volume and interaction

📈 In-Analysis
Observations
Posts with hashtags like #Fitness, #Education, and #Challenge show strong engagement

Reels and Tweets deliver better like-to-view ratios

Some hashtags are overused with low impact (e.g., #Viral, #Gaming)

Analysis Tools
Excel Pivot Tables

Grouped bar charts

SUMIFS, COUNTIFS, and VLOOKUP for segment analysis

✅ Post-Analysis and Insights
Confirmed Findings
Engagement levels correlate strongly with content format and platform

Fitness-related content remains a universal top performer

Reels outperform Shorts in average engagement per post

Unexpected Findings
Tweets performed surprisingly well in likes, close to Reels

Certain viral hashtags delivered low returns despite high visibility

📊 Data Visualizations & Charts
Engagement by Content Type (Bar Chart)

Platform Share of Total Views (Pie Chart)

Top 10 Hashtags by Engagement Level (Table)

Content Type vs Likes & Shares (Stacked Chart)

All visuals were created in Excel and are available in the /charts directory.
![DASHBOARD 8](https://github.com/user-attachments/assets/de5d7bd1-8fa2-4e05-a404-9fb48fcf966d)


🧠 Recommendations and Observations
Prioritize Reels and Tweets for campaigns aiming at higher interaction

Focus hashtag usage on high-ROI topics like #Fitness, #Education


Limit generic or oversaturated hashtags

Consider regional targeting for North America and UK audiences

🧾 Conclusion
Key Learnings
Format and hashtag selection significantly impact engagement

Reels, despite fewer posts, often outperform longer videos in likes

Limitations
No timestamps to track time-based trends

No demographic segmentation

Future Research
Add time dimension to track trend evolution

Include more granular regional and age-group data

📚 References & Appendices
Data Source: Internal platform analytics export

Tools: Microsoft Excel

Charts and Summary Files: See /charts and /summary_tables
