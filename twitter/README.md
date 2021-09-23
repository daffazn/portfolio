# Twitter Keyword Analysis

I extracted +300,000 tweets containing keyword of Cristiano or Ronaldo (or both) at the day of his first match with Manchester United after his return. I use Tweepy Python library to access the Twitter API. The latest Tweepy stable release can only access the Twitter API v1.1, but I wanted to access the v2 because it gives more detalis about the tweet. So I decided to use the latest beta version of Tweepy.

I found an error when I was requesting specific data queries for the tweets. After exploring the library's code, I found the source of error and modify the code. So in the end, I used this modified library to extract the tweets. I also have included the modified file in this repository.


Extracted tweets: https://drive.google.com/file/d/1J_Y2dcgQ3oIiefI0flHIKico_KBQtTmo/view?usp=sharing

If you want to extract the tweets manually, replace the pagination.py file in "...\Python\Python38\Lib\site-packages\tweepy\" with the pagination.py file in this repository.
