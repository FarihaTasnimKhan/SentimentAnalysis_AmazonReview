# SentimentAnalysis_AmazonReview
Amazon is a multinational technology company and the world’s largest online retailer and marketplace. Every day, Amazon sends out over 1.6 million product deliveries. Such high Amazon sales indicates that the customer reviews on the Amazon website are high as well. However, it is difficult and very time consuming to analyze millions of reviews manually by humans. This is why businesses use sentiment analysis models to analyse, evaluate, and learn from millions of customer reviews fast and find if their customers are satisfied with their product and service, or if it needs improvement.
For performing sentiment analysis, 3 models in total have been implemented, all of which are pre-trained. The models have been implemented on a dataset of over 34,000 Amazon customer reviews. The models are the VADER (Valence Aware Dictionary for Sentiment Reasoning) model, bert(Bidirectional Encoder Representations from Transformers) -base-multilingual-uncased-sentiment model and emotion-english-distilroberta-base. After implementing both the models, both models have been compared and in order to do so, a subset of the Amazon dataset has been taken randomly with 50 observations and has been labelled manually to form a ground truth dataset. Next, both the models have been applied on the ground truth dataset to find the sentiments. Next, the sentiments labels classified by the pre-trained models and the manually labeled sentiments have been compared and an accuracy has been found to find which one is more accurate, after which the bert-base-multilingual-uncased-sentiment model has been found to have a higher accuracy of 70%.
Next the models have been further compared by comparing the sentiment labels of VADER model and bert-base-multilingual-uncased-sentiment model side by side, to see which model is more suitable among which bert-base-multilingual-uncased-sentiment model has been found to be more suitable for this project, and the reason for this may be due to being specially fine-tuned on product reviews and hence is more able to correctly classify sentiments for Amazon product reviews. 
Lastly, emotion analysis has been performed to dive deeper into sentiment and further know about how a customer exactly felt about the product, using the Emotion English DistilRoBERTa-base model.