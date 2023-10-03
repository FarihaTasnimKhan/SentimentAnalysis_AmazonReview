# SentimentAnalysis_AmazonReview
Amazon is a multinational technology company and the world’s largest online retailer and marketplace. Every day, Amazon sends out over 1.6 million product deliveries. Such high Amazon sales indicates that the customer reviews on the Amazon website are high as well. However, it is difficult and very time consuming to analyze millions of reviews manually by humans. This is why businesses use sentiment analysis models to analyse, evaluate, and learn from millions of customer reviews fast.


For performing sentiment analysis, 3 models in total have been implemented:
1. The VADER Model
2. The bert(Bidirectional Encoder Representations from Transformers) -base-multilingual-uncased-sentiment Model
3. The emotion-english-distilroberta-base Model

All these models are pre-trained. These models have been implemented on a dataset of over 34,000 Amazon customer reviews. After implementing both the models, both models have been compared and in order to do so, a subset of the Amazon dataset has been taken randomly with 50 observations and has been labelled manually to form a ground truth dataset. Next, both the models have been applied on the ground truth dataset to find the sentiments. Later, the sentiments labels classified by the pre-trained models and the manually labeled sentiments have been compared and an accuracy has been found to find which one is more accurate. Finally, it is found that the bert-base-multilingual-uncased-sentiment model has a higher accuracy of 70%.

Next the models have been further compared by comparing the sentiment labels of VADER model and bert-base-multilingual-uncased-sentiment model side by side, to see which model is more suitable among which bert-base-multilingual-uncased-sentiment model has been found to be more suitable for this project, and the reason for this may be due to being specially fine-tuned on product reviews and hence is more able to correctly classify sentiments for Amazon product reviews. 

Lastly, emotion analysis has been performed to dive deeper into sentiment and further know about how a customer exactly felt about the product, using the Emotion English DistilRoBERTa-base model. The emotions classified are joy, anger, surprise, neutral, fear, disgust, sadness. Lastly, in order to find insights from the sentiment classification results, SQLite3 has been used to perform queries and find insights. The findings has also been presented visually by using Python to display the results in the form of charts and plots.
