# Trending Youtube Video Analysis
## Motivation:
&nbsp; &nbsp; YouTube (the world's most popular video sharing website) maintains track of the top trending videos on the platform. According to Variety magazine, "to pick the year's top-trending videos, YouTube applies a variety of factors, including tracking viewer interactions" (number of views, shares, comments and likes). This study provides a detailed investigation of Trending YouTube Video Statistics. It will help in addressing business questions such as which titles are most liked and disliked on YouTube. We used Kaggle datasets for this, followed by data cleaning, databasegeneration, data visualization, and the development of a Machine Learning model for YouTube view forecasting.

## Dataset Description
&nbsp; &nbsp; The Kaggle website provided the dataset. Below is a link to the source. https://www.kaggle.com/datasets/datasnaek/youtube-newThe daily YouTube video trends through time are detailed in this dataset (and counting). Data from the RU, MX, KR, JP, and IN regions are supplied for the same time period (respectively, Russia, Mexico, South Korea, Japan, and India). The data for each region is saved in a separate file. Theinformation comprises the video's title, the channel name, the date and time it was published, tags, views, likes, dislikes, a description, and the number of comments.
A category id field, which varies by region, is also present in the data. Find the associated JSON to retrieve the categories for a certain video. These files are dispersed throughout the dataset's fiveregions.


## Highlights of procedure:
&nbsp; &nbsp;1️⃣Efficiently implemented ETL process<br/>
&nbsp; &nbsp;&nbsp; &nbsp;• Created pipelines to store data in S3 buckets<br/>
&nbsp; &nbsp;&nbsp; &nbsp;• Created ETL pipeline to join tables in AWS Glue Studio<br/>
&nbsp; &nbsp;&nbsp; &nbsp;• Used AWS Athena to query databases<br/>
 
&nbsp; &nbsp;2️⃣Data Visualization using Power BI<br/> 
&nbsp; &nbsp;&nbsp; &nbsp;• Region which has most liked and disliked titles.<br/> 
&nbsp; &nbsp;&nbsp; &nbsp;• Ratio of Number of likes upon number of views.<br/> 
&nbsp; &nbsp;&nbsp; &nbsp;• Sum of likes by region.<br/> 
&nbsp; &nbsp;&nbsp; &nbsp;• Region with most disabled comments. <br/> 
