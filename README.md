# Twitter-Crawler
Streaming APIs give us low latency access to Twitter’s global stream of Tweet data in almost real-time manner. This code is implemented with respect to tweepy library. 

- In order to let this code work, you have to create your own Twitter access token, visit (https://dev.twitter.com/webhooks/access-tokens) to understand why you need them and how to create your own.

-Then, Paste the (consumer_key, consumer_secret, access_token and access_secret) tokens in config.py with your generated configuration tokens from twitter developer website.

-Make sure to create a file to save the crawled data in, by using command (mkdir data).

-To run the code : use the following command by passing your requested keywords to crawl lively tweets about it.
python twitter_stream_download.py -q (your keyword) -d data

example: If you want to crawl up-to-dates tweets about e-learning, then (python twitter_stream_download.py -q #e-learning -d data) 
has to be run using your cmd.


# Dataset 

You can download the dataset (Tweets for keyword 'MOOC/s' over the period 3 to 31 of July 2017 resulting in more than 43,000 full structured time-stamped tweets). 
MOOC: stands for Massive Open Online Courses.

 https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910%2FDVN%2FFJXK56)



# Figures


Figure showing the results from the web crawler- it should show less activities on eLearning while higher frequncy from the hastag "game of throne"
