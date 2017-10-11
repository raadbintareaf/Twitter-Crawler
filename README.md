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
 
- Tweets for #MOOC/s over the period 3 to 31 of July 2017 resulting in more than 43,000 full structured time-stamped tweets. 
- #GameOfThrones hashtag on the third day of releasing (Jul-18 2017) the 7th season, results a 4447 tweet within only 16 minutes! 

(This meet one of our hypothesis which assumes that social media users are more interested of being updated about entertainment contents over educational matterial).

# Figures


**Linkedin post** : a figure shows a post at Linkedin platform, which the post contains an educational video material.
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/linkedin%20post.PNG)







**Linkedin post activity**: result of the engagement at the Linkedin post over the last month (September). 
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/linkedin%20post%20activity.PNG)







**Twitter Post**: a figure shows a tweet posted at twitter platform over a month. The tweet contains a link for same educational video that Linkedin have. 
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/tweet%20post.PNG)






**Twitter post activity**: result of posting this tweet for over a month, contains counter for how many likes, link clicks and hashtag clicks.
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/tweet%20activity.PNG)





**2g_3g_4g_coverage_map**: containts a map that address all countries in the world with the current internet network coverage type (2G: Red, 3G:Blue and 4G:Yellow). *http://extensia-ltd.com/africa-africa-world-looks-like-2g-3g-4g/
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/2g_3g_4g_coverage_map.png)


**MOOCs global covereage by HPI**: Learning analysis shows less usage of elearning platforms in Africa compared to the penetration and the popularity of social networking sites worldwidely. ![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/mooc_coverage.PNG)

**Three_Hashtags _Visualization**: a hashtag network for (#OpenHpi, #HPI_DE, #OpenSAP) over the period 20th-27th/June/2017.  
![img](https://github.com/raadbintareaf/Twitter-Crawler/blob/master/Three_Hashtags%20_Visualization.png)





  
