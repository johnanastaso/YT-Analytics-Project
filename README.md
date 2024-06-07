# YouTube Channel Analysis Project
 
Project Overview
This project aims to analyze the YouTube channels and videos of four popular creators: Lex Fridman, Andrew Huberman, Chris Williamson, and Alex Hormozi. Using the YouTube API, I gathered data to gain insights into their content, performance, and audience engagement. This analysis may be useful for informing the creators' future video strategies. For example, the analysis revealed that shorts perform really well, and one of the channels has not produced many short videos, suggesting an opportunity to create more.

Goals
Data Collection: Acquire data from YouTube API for the four channels.
Data Transformation: Clean and transform the data for analysis.
Exploratory Data Analysis (EDA): Visualize and analyze the data to uncover trends and insights.
Dashboard Creation: Develop an interactive Power BI dashboard to present findings.

Data Collection
The data was acquired using the YouTube API, which included details about videos, such as titles, views, likes, comments, and upload dates. The data collection process involved:

Setting up API credentials.
Writing scripts to fetch data from the API.
Storing the data in a structured format for analysis.
Data Transformation
After collecting the data, I performed the following transformations:

Cleaning the data to handle missing or inconsistent values.
Normalizing data formats.
Aggregating statistics per channel and video.
Exploratory Data Analysis (EDA)
The EDA was conducted in a Jupyter Notebook, where I:

Loaded the transformed data.
Created various visualizations to explore trends and patterns.
Analyzed key metrics such as views, likes and video duration

Dashboard in Power BI
I loaded the transformed data into Power BI and created a 2-page interactive dashboard. This dashboard provides:

Overview Page:
Key Metrics: Subscribers, Total Videos, Likes per Video, Views per Video, Average Video Duration.
Views and Subscribers by Channel: A comparison of views and subscribers across the four channels.
Top 5 Most Viewed Videos: Highlighting the videos with the highest view counts.
Distribution of Total Videos by Duration: Mapping the distribution of videos based on their duration.
Engagement Page:
Engagement Ratios: Metrics such as Like to View ratio, Comment to View ratio, and overall Engagement Ratio.
Heatmap for Duration Categories vs. Engagement Metrics: Visual representation of how different video duration categories correlate with engagement metrics.
Total Likes per Duration Category: Analysis of the total number of likes received per video duration category.
Views per Video & Total Videos per Category: Insights into views per video and the total number of videos across different categories.
Project Files

Channel_Stats.xlsx: Excel file containing channel data.
README.md: This file, providing an overview of the project.
Video_Stats.xlsx: Excel file containing video data.
YT_Analytics_Project.pbix: Power BI file with the interactive dashboard.
YT_Analytics_Project_EDA.ipynb: Jupyter Notebook containing the exploratory data analysis.
YT_Analytics_Project_Extract_data_with_API.ipynb: Jupyter Notebook for extracting data using the YouTube API.
Conclusion
This project showcases the process of collecting, transforming, and analyzing YouTube data to derive meaningful insights. The interactive dashboard in Power BI provides a comprehensive view of the performance and engagement metrics for the selected channels.

Next steps

Combining the findings of this project with historical data regarding the subscribers each channel acquired throughout the years we could perform predictive analysis with models to predict future channel performance (videos & subscribers)
Sentiment Analysis: Perform sentiment analysis on video comments to gauge audience reactions.
Expand Channel List: Include more channels for a broader analysis.

Feel free to explore the project and reach out if you have any questions or suggestions!
