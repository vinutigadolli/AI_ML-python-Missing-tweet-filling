# AI_ML-python-Missing-tweet-filling
Random Forest applied in this ML project

Task:
1. Identify the intent of tweet using one of the ML models.

Specifications of Task
● Find the intent of the tweets that are missing.
● There are tweets with identified intent: Appreciation, Community, Done,
Giveaway, Interested, Launching Soon, PinkSale, PreSale, Whitelist
● Use these tweets to train your model and assign the intent to the tweets with
missing intent.
● Show your result, fill rate, code and describe the process.

Appraoch:
dataset info :
0 to 127453
Data columns (total 4 columns):
 #   Column            Non-Null Count  Dtype 
---  ------            --------------  ----- 
 0   id                127453 non-null  int64 
 1   tweet_created_at  127453 non-null  object
 2   tweet_text        127453 non-null  object
 3   tweet_intent      96364 non-null  object
 
 
we have acheived accuracy of 92% on test set and 98% on train set using Random forest classifier
there is a slight overfitting but the accuracy of 92% is pretty acceptable.

Please Go through notebook to make yourself.



