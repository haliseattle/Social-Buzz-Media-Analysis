# Social-Buzz-Media-Analysis
Social Buzz Media Analysis
Company Overview and Project Objective
Social Buzz – an emerging social media company needs to adapt quickly and effectively. Accenture’ has begun a 3-month POC focusing on the following tasks:
* Audit of big data practice
* Recommendations for IPO
* Analysis of Social Buzz’s most popular content
## Scenario
Social Buzz, a fast-growing social media platform, receives over 100,000 posts per day, totaling more than 36.5 million pieces of content annually. With such an overwhelming volume of user-generated content, the company sought to understand what types of content resonate most with users in order to inform marketing strategy and guide brand partnerships.

As the data analyst on the project, my role was to analyze content performance trends to uncover which categories drive the most engagement and identify opportunities for strategic collaboration with brands, particularly in high-interest areas like food, science, and lifestyle.

## Ask
* Which content categories generate the most user engagement on Social Buzz?
* Are there recurring themes or topics within the most popular content?
* What do the most engaging categories reveal about user interests and behavior?
* How can these insights inform marketing strategies or potential brand partnerships?
* What content types or themes could be prioritized to increase platform engagement?

## Clean and Process Data 
* Cleaned an Excel dataset containing 25,000+ records from 2020 and 2021.
* Removed rows with missing or incomplete fields to maintain data integrity.
* Used VLOOKUP to merge data across multiple tables (reaction types, popular categories, and content) by linking shared attributes such as content ID and category.
* Ensured that each reaction was matched with a corresponding sentiment and score; removed any data points that lacked this information to ensure accuracy in sentiment analysis.

## Observations 

<img width="787" height="599" alt="Reaction by Month" src="https://github.com/user-attachments/assets/870d9fc2-fe55-42e5-a5ed-9f0ce1feb677" />

Analysis: The highest number of reactions occurred in May, while the lowest was observed in February. There is a general upward trend over time, indicating increasing engagement. However, aside from this growth, the number of reactions remains relatively stable across most months.

<img width="1027" height="599" alt="Reaction By Hour" src="https://github.com/user-attachments/assets/e7568657-2146-490c-813c-bae6d8f6aed2" />

Analysis: Throughout the day, the total number of reactions shows a slight decline from 12 AM to 11 PM. The highest engagement occurs in the early morning hours between 4 AM and 9 AM, while the lowest is observed between 10 AM and 2 PM. Despite these fluctuations, overall reaction levels remain relatively consistent throughout the day.

<img width="1876" height="869" alt="Content Type Reaction" src="https://github.com/user-attachments/assets/3ffab08e-3736-46a5-bf6d-f1d6fce3ad7e" />

Analysis: When analyzing sentiment across the week, positive reactions are the most frequent, while neutral reactions are the least. For both positive and neutral sentiments, there is a general trend of decreasing engagement at the start of the week, followed by an increase toward the weekend, with a noticeable spike in positive reactions during the weekend. In contrast, negative reactions remain high from Monday to Thursday, then decline and slightly rise again on Friday and over the weekend.

<img width="1455" height="850" alt="Percentage Total Accross Categories" src="https://github.com/user-attachments/assets/8899f153-3f12-4b4d-8c5a-2a9ad3b8fb44" />

Analysis: Based on the percentage of total reactions across categories, the top five are Animals, Science, Healthy Eating, Food, and Technology which account for about  36% of all reactions, indicating a strong concentration of engagement in these areas. In contrast, categories like Studying, Dogs, Tennis, Veganism, and Public Speaking rank lowest in terms of reaction share which suggests relatively lower audience interest or visibility.

<img width="1876" height="869" alt="Content Type Reaction" src="https://github.com/user-attachments/assets/5ab74e50-2a3a-4e14-9340-09a9c2b0c24f" />

Analysis: When examining reactions by content format, photos (26.8%) and videos (25.4%) receive the highest levels of engagement, followed by GIFs and then audio, which has the fewest reactions. This suggests that users are more responsive to visual content, particularly photos and videos. However, the differences in reaction levels across formats are relatively minor.

## Summary of Social Media Reaction Analysis

Engagement and Top Categories:
- Negative reactions are the most common, followed by positive, with neutral being the least and highest toward the weekend, with a noticeable spike in positive sentiment on weekends.
- The top five categories—Animals, Science, Healthy Eating, Food, and Technology—make up about  36% of total reactions, suggesting strong user interest in real-life, informative, and emotionally resonant content.
  
Monthly and Daily Trends:
- The highest number of reactions occurred in May, and the lowest in February.
- There is a general upward trend in engagement over time, though reaction levels remain relatively steady month to month.
- Reactions slightly decrease throughout the day and peak occurs early in the morning while the lowest engagement late in the day.
  
Content Format Trends:
- Photos and videos receive the most reactions, while audio receives the least.
- This suggests users engage more with visual content, though differences across formats are not extreme.

## Plan of Action and Recommendations 
Based on the analysis of category trends, engagement patterns by month and time of day, and content format performance, here are the top three recommendations to increase engagement across Social Buzz.

Leverage Top-Performing Categories:

- Food-related content emerged as a consistent theme across top categories, with Food and Healthy Eating collectively accounting for nearly 40% of the most popular content. This presents a strategic opportunity to collaborate with food and lifestyle brands to drive targeted engagement and sponsored content partnerships.
  
Prioritize Visual Content (Photos & Videos):
- Since photos and videos receive the highest engagement, focus your campaigns around eye-catching visual content.
- Consider using short-form videos to highlight key messages especially for product launches or educational content.
  
Post During Peak Hours & Days:
- Schedule posts during early morning hours when engagement is highest.
- For positive sentiment, focus posts toward the weekend, especially Friday–Sunday when users are more responsive and emotionally receptive.

## Next Steps
While these insights offer a valuable starting point, expanding the analysis to larger datasets and real-time metrics will provide a more dynamic view of user behavior. Our team can support the development of a scalable, real-time analytics framework to better inform content strategy and marketing decisions.




