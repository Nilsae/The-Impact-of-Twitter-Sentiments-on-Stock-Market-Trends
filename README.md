# The-Impact-of-Twitter-Sentiments-on-Stock-Market-Trends

This is the final project of the Information Technology Fundamentals course under the supervision of Dr. M . Manshaei.

We collected two datasets from Twitter, one consisting of data labeled on the vibe of the tweets which had any topic, and another, unlabeled data of market-relevant tweets.
We used the first dataset to build three supervised models: LSTM, Random Forest, and Naive Bayes. Then we used our trained models to label the second dataset.

We collected the financial data of the five most popular stock markets: Apple, Facebook, Tesla, Amazon, and Microsoft. Then we defined a variable bullishness to represent the ratio of the positive tweets to the negative ones for each day and scaled this bullishness variable with the amount of the return value of that stock on the day after that, which was the representative of our financial data. 

Then we evaluated the possible impact of the tweets on the markets using the synchronous diagram of bullishness and return variables.
