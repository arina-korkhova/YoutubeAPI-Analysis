# 🔺 Channels' Video Data Analysis Using YouTube API 🔺

<p align="center"> <img src="https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/youtube.png" align="center" alt="Illustration" width="50%" height="5%" /> </p>

## 🧧 Introduction

Youtube is the largest global online video sharing and social media platform launched on February 14, 2005. It is owned by Google, and is the second most visited website, after Google Search. 

It is a myth how the Youtube algorithm works, what makes a video get views and be recommended over another. There are many speculations around the success of a video on Youtube, for example if the video has more likes or comments, or if the video is of a certain duration. 

I have stumbled upon an [article](https://www.tastyedits.com/best-cooking-channels-youtube/#:~:text=Our%20top%2010%20cooking%20channels,Cuisine%2C%20and%20Pro%20Home%20Cooks.) featuring the Top 10 Best Cooking Channels on YouTube in 2022. And I began to wonder why certain channels are more popular than others. So, apart from the content itself (which is undoubtedly the most crucial factor of success), I decided to explore the statistics of 3 successful cooking Youtube channels. Or perhaps there is a secret dish that might bring the cook glory and fame?

## 🔴 Aims and objectives
Within this project, I am exploring the following:

* Getting to know [Youtube API](https://developers.google.com/youtube/v3) and how to obtain video data. 
* Analyzing video data of 3 channels and see which features correlate most with views, for example:
	* Does the number of likes and comments correlate with a number of views?
	* Does the video duration matter?
	* Does title length matter?
	* Does the number of tags matter?
	* On which days in the week do they upload new videos?
	* What are the best performing videos?
	* What are the worst performing videos? 
	* What are the most popular dishes and ingredients? (using NLP)

**👣 Steps of the project**
1. Obtain video data via Youtube API for the channels (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Data Prepocessing and engineering additional features for analysis
3. Exploratory Data Analysis

**⛔ Data Quota**

Per [Youtube Data API Guide](https://developers.google.com/youtube/v3/getting-started) projects that enable the YouTube Data API have a default quota allocation of 10,000 units per day. If you reach the quota limit, you can request additional quota by completing the Quota extension request form for YouTube API Services. For this reason I limited the amount of channels I analyze to three to avoid worrying about exceeding the limit.  

## 🔶 Some Exploratory Data Analysis Results

* Does the number of likes and comments matter for a video to get more views?

![Views vs. Comments and Likes](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/ViewsVsCommentsAndLikes.png)

![Comment and Like Ratio](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/CommentAndLikeRatio.png) 

* Does the video duration matter for views and likes/comments?

![Video Duration](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/Duration.png)

![Comments And Likes vs. Duration](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/CommentsAndLikesVsDuration.png)

* Does title length matter for views?

![Title Length vs. Views](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/TitleLengthVsViews.png)

* Does number of tags matter for views?

![Tags vs. Views](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/TagsVsViews.png)

* When are most videos uploaded?

![Best Weekdays](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/BestWeekdays.png)

* What are the best performing videos among all three channels?  

![Best Videos](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/BestVideosOfAllChannels.png)

* What are the most popular dishes and ingredients?

![Popular Words](https://github.com/arina-korkhova/YoutubeAPI-Analysis/blob/master/images/PopularWords.png)

## 🟥 Conclusions

In this project, we have explored the video data of three popular Cooking channels and discovered a multitude of noteworthy insights that could be beneficial to anyone launching a YouTube channel in cooking or another subject:

* The more likes and comments a video has, the more views the video gets. Likes seem to be a better gauge than comments and the more views the video has, the more likes people will leave.
* The best performing videos are under 20 minutes.
* Most-viewed videos tend to have average title length of 30-70 characters.
* Most videos have between 15 and 35 tags.
* Videos are rarely uploaded on Mondays and Saturdays. Tuesday is the most popular weekday. 
* Most popular dishes and ingredients are Homemade Chicken, Pie, Cookie, Sandwich, Chocolate, Fried Food. As well as Burger, Egg, Soup, Taco, Pizza, Bread, Cheese, Cake, Rice, Beef.
