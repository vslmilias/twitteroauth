from twitter import *
api = Twitter(auth=OAuth(access_token,\
access_token_secret,\
consumer_key,\
consumer_secret))
result = api.search.tweets(q="coffee")
for tweet in result['statuses']:
print tweet['text']
