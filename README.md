# syrazy_twitter_bot
Two Twitter bots encompass this repository. 

The first of the two is titled tweepy_mention_bot.
  - This Twitter bot completes two actions dependent on certain requisites
  1. The bot streams Twitter for mentions a.k.a Tweets that include the string: '@syrazynews' 
  2. The bot saves the tweet ID along with the tweet's user information
  3. The bot will then check the tweet to see if it contains the string: 'syrazy'
      - if True: the bot will reply AND follow the user
  4. The bot will then keep streaming to look for the next mention

The second bot is titled tweepy_mention_bot.
  - This Twitter bot completes two actions dependent on certain requisites
  1. The bot streams all Tweets for any that contain the string: 'syrazy'
  2. The bot saves the tweet ID along with the tweet's user information
  3. The bot will reply AND follow the user
   4. The bot will then keep streaming to look for the next tweet
   
// AS you can see the first bot is a subset of the second bot.
Therefore only the second bot will be functional but it's suggested to 
practice with the first bot. 
  
