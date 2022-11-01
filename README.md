# Custom NLP Model for Sentiment Analysis

As per [Kaggle notebook](https://www.kaggle.com/slythe/twitter-sentiment-analysis-custom-model)

## Project Summary 
Extract, Process and Predict the sentiment of Twitter tweets referencing South Africa's top 5 banks.

Multiple models were created and tested to predict sentiment of tweets as either postive, neutral or negative

Note: 
1. Multiple datasets were used as training of the model, with Sentiment 140 being the main contributor of tweets (1.6 million) 
2. Proof of concept version was completed using a pretrained model (Textblob)

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
