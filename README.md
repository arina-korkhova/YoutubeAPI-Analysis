# Youtube API Analysis

# Aims and objectives
Within this project, I am exploring the following:

* Getting to know [Youtube API](https://developers.google.com/youtube/v3) and how to obtain video data. 
* Analyzing video data of TED channel and see which features correlate most with views, for example:
  * What are the best performing videos? Are they most commented?
  * What are the worst performing videos? 
  * Does the number of likes and comments correlate with a number of views?
  * Does the video duration matter?
  * Does the number of tags matter?
  * Does title length matter?
  * On which days in the week do they upload new videos?
  * Which popular topics are being covered in the videos? (using NLP techniques)

# Steps of the project
1. Obtain video data via Youtube API for the TED channel (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
2. Data Prepocessing and engineering additional features for analysis
3. Exploratory Data Analysis

# Conclusions
In this project, we have explored the video data of the TED channel and revealed many interesting findings:

* The more likes and comments a video has, the more views the video gets.
* Most videos have between 5 and 25 tags, mostly around 10.
* Most-viewed videos tend to have average title length of 40-70 characters. Too short or too long titles have less views.
* Videos are normally uploaded on weekdays (Monday to Friday). Saturday and Sunday are not a popular time for posting new videos.
