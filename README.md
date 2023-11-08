# Tusker Oktober Fest
Tusker Oktober FEST: Twitter Sentiment and Engagement Analysis.

The purpose of this project is to demonstrate data scraping and sentiment analysis using Twitter's API and Tweepy.

# Key Takeaways
* Using Tweepy to access the Twitter API.

* Using pandas to put the data scrapped into a data frame and everything that has to do with the data frame.

* Counter from collections to get the counts for each hashtag and cast(collections is inbuilt, so you don't need to install it, just import counter)

* A function was created using regex expression's re.sub, to extract hashtags, cast and preprocess the data

* How well are the Sentiments distributed?
To know more about the sentiments,
TextBlob was used to get the subjectivity and polarity of the tweets.
Polarity tells the sentiments of the tweets, which tweets are negative, positive, or neutral, whereas subjectivity tells how subjective or opinionated the tweets are.

* What were the most frequent words used in the tweets?
To know the most frequent words used in tweets, you would have to create a wordcloud.
A wordcloud is a visualization where the more specific words appear in the text, the bigger and bolder it appears in the wordcloud.
1. Numpy to convert the image to an array
2. pillow (PIL) to import an image for the wordcloud, using its image class


# Installation
* Clone this repository
* Install python jupyter notebook or any IDE of your choice
* Install
1. tweepy, 
2. re, 
3. pandas, 
4. matplotlib, 
5. textblob
6. wordcloud.
7. numpy
8. pillow
