# community-sentiment-analysis

Goal of the project was to familiarize myself with NLTK:s VADER Sentiment Analysis tool
[[VADER](https://github.com/cjhutto/vaderSentiment)] 
and to explore social media communities based on the sentiment of the material posted in them.
Reddit was chosen as the social media community as its different subreddits 
form a diverse set of communities, which should reflect in the sentiment scores.
Reddit also provides PRAW-api [[PRAW](https://praw.readthedocs.io/en/latest/)]
, which helps in the easy extraction of different posts and comments. Unfortunately
PRAW-api is rate limited, which makes it slow for for extracting large quantities of
data fast.  

## Examples

![Screenshot](pics/Compound_sentiment_score.png)
![Screenshot](pics/Negative_sentiment_score.png)
![Screenshot](pics/Positive_sentiment_score.png)
![Screenshot](pics/Positive_sentiment_score.png)
![Screenshot](pics/Compound_sentiment_score_of_1000_largest_subreddits.png)


