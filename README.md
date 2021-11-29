# Custom NLP Model for Sentiment Analysis

As per [Kaggle notebook](https://www.kaggle.com/slythe/twitter-sentiment-analysis-custom-model)

## Project Summary 
Train model to predict sentiment analysis. This model will the be used to predict Tweets that reference one of the top 5 banks in South Africa.

***Note***: I used mutiple datasets to do this with Sentiment 140 being the main contributor of tweets (1.6 million)
This was automatically labled (using emoticons) and doesnt have neutral tweets labled

**Note** Proof of concept version was completed using a [pretrained model](https://github.com/Slyth3/Sentiment-analysis-on-South-African-Banks-POC) (Textblob) 

## Datasets used
1. [Sentiment140](https://www.kaggle.com/milobele/sentiment140-dataset-1600000-tweets)
1. [Twitter and Reddit](https://www.kaggle.com/cosmos98/twitter-and-reddit-sentimental-analysis-dataset) 
1. [US airlines](https://www.kaggle.com/crowdflower/twitter-airline-sentiment) 
1. [Apple sentiment](https://www.kaggle.com/slythe/apple-twitter-sentiment-crowdflower) 

## Known issues with sentiment analysis:
* Sarcasm - "thanks FNB, now I cant open my account cause its frozen" 
* Comparison of entities  - "Capitec is the worst, you should use Standard Bank" 
* Training data on non-South African tweets  - Jargon and lingo is different
* Language usage - multiple languages are used in South Africa

Reference notebooks:
* [Full sentiment analysis](https://www.kaggle.com/paoloripamonti/twitter-sentiment-analysis/notebook) 
* [beginners notebook](https://www.kaggle.com/stoicstatic/twitter-sentiment-analysis-for-beginners)
