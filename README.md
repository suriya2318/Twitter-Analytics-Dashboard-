# Twitter Analytics Dashboard (Interactive Power BI Dashboard for Twitter Performance Insights)
## Project Objective
The goal of this project is to create a comprehensive and interactive Twitter Analytics Dashboard using Power BI. This dashboard helps social media analysts, marketers, and stakeholders monitor and optimize tweet performance, track audience engagement, and identify patterns to improve content strategy. The dashboard visually breaks down key Twitter metrics such as impressions, likes, retweets, media views, URL clicks, and hashtag engagement, enabling data-driven decisions for content scheduling and format choices.

## Dataset Used
- <a href="https://github.com/suriya2318/Twitter-Analytics-Dashboard-/blob/main/Twitter%20Dataset.csv"> Twitter Dataset </a>

## Key Business Questions (KPIs)
•	What is the average engagement rate across tweets?

•	Which days and hours produce the highest engagement?

•	What tweet types (text, image, video, poll) perform best?

•	What hashtags and URLs receive the most clicks?

•	How does user engagement vary by day of the week?

•	Are media tweets driving more views and interactions?

•	When is the best time to post for maximum reach and engagement?

•	What content can be improved based on click and impression data?

## Process
### 1. Data Cleaning & Preparation
•	Handled missing/null values and removed duplicates.

•	Standardized formats for date, time, and tweet types.

•	Created new calculated columns: day of week, hour, tweet format.

•	Ensured metrics like impressions, media views, and engagements were numerical and clean.

### 2. Data Modeling in Power BI
•	Loaded cleaned dataset into Power BI.

Created DAX measures for:

  •	Engagement Rate
  
  •	Total Likes, Retweets, Clicks
  
  •	Avg. Engagement by Tweet Type
  
  •	Best Time to Post metrics

•	Built relationships and hierarchies (e.g., Date hierarchy: year > month > day > hour).

### 3. Visualization & Dashboard Design
•	Built two core dashboard pages:

•	Overview Page for high-level metrics

•	Engagement Page for detailed user interaction

•	Used slicers for month and day-based filtering.

•	Applied best practices:

•	Consistent color themes

•	Simple, intuitive visuals

•	Tooltips and labels for clarity

•	Clean layout with minimal clutter

## Dashboards Overview
### Page 1: Twitter Analysis Overview
This page gives a high-level summary of the overall performance of the Twitter account across tweets, engagement, impressions, and user interactions.

• Tweet Count (Card): Shows the total number of tweets published, helping understand content volume.

• Media Views (Card): Displays total views on tweets with media, indicating how attractive media content is to viewers.

• Avg Engagement Rate (Card): Reveals how engaging tweets are on average, calculated using likes, replies, retweets vs. impressions.

• Impression Count (Card): Total number of times tweets were shown to users.

• URL Clicks by Tweet (Bar Chart): Ranks tweets based on how many times users clicked on the links, highlighting top-performing content.

• Likes (Gauge Chart): Shows the total likes received, giving a sense of positive audience reaction.

• Max Retweets (Gauge Chart): Displays the highest number of retweets for a single tweet—reflects virality potential.

• Tweet by Week (Area Chart): Shows the number of tweets made each day of the week, helping identify the most active days.

• Impressions by Week (Line Chart): Displays daily impressions, allowing quick visual correlation with tweeting days.

• Hashtag, URL, User Profile Clicks (Pie Chart): Breaks down user interactions—how often people clicked hashtags, URLs, or user profiles. Useful to understand what type of clickable content works best.

• Month Filter (Slicer): Allows users to filter all the visuals based on the selected month (June–October), supporting time-based analysis.

![Twitter Analysis Overview](https://github.com/user-attachments/assets/7cd587a8-3e53-4bc0-86d4-c05e87b5a149)

### Page 2: Engagement & Media Analysis
This page drills down into audience engagement by weekday and analyzes how media affects performance.

• Engagement Count (Bar Chart): Shows total engagements (likes, replies, retweets) by day of the week—helps identify which days generate the most interaction.

• Media Engagement vs. Media View (Clustered Bar Chart): Compares how often media was viewed versus how often users engaged with it. Helps assess media content effectiveness.

• Likes and Replies by Day (Card List): Lists total likes and replies per day to understand specific days that drive more user interaction.

• Month Filter (Slicer): Same as in Page 1; allows monthly filtering of all metrics for consistent comparative analysis.

![Engagement   Media Analysis](https://github.com/user-attachments/assets/dde663a4-1a1f-4af2-ae0f-e42b9e8e6b05)

## Project Insights
• Tweets posted on Thursday and Tuesday generated the most engagement.

• Media tweets (image/video) had significantly higher interaction rates than plain-text tweets.

• Sunday showed lowest engagement and impressions, suggesting it's not ideal for posting.

• Certain tweets with specific hashtags and links led to more profile or website clicks.

• A clear "best time to post" trend emerged around mid-week mornings, based on the heatmap analysis.

• Engagement rate is modest overall, suggesting room for testing more interactive or visual tweet content.

## Final Conclusion
This Twitter Analytics Dashboard empowers social media professionals with actionable insights into audience behavior and content performance. By identifying the best times and formats to post, teams can optimize campaigns and drive higher engagement. The data-driven approach helps reduce guesswork, improve ROI on content strategies, and tailor posts to audience preferences. It’s a scalable tool that can evolve with additional features like competitor comparison or sentiment analysis.
