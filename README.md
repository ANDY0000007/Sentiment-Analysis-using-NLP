# Sentiment-Analysis-using-NLP
Sentiment analysis is perhaps one of the most popular applications of natural language processing and text analytics with a vast number of websites, books and tutorials on this subject. Typically sentiment analysis seems to work best on subjective text, where people express opinions, feelings, and their mood. From a real-world industry standpoint, sentiment analysis is widely used to analyze corporate surveys, feedback surveys, social media data, and reviews for movies, places, commodities, and many more. The idea is to analyze and understand the reactions of people toward a specific entity and take insightful actions based on their sentiment.

Sentiment analysis is also popularly known as opinion analysis or opinion mining. The key idea is to use techniques from text analytics, NLP, Machine Learning, and linguistics to extract important information or data points from unstructured text. This in turn can help us derive qualitative outputs like the overall sentiment being on a positive, neutral, or negative scale and quantitative outputs like the sentiment polarity, subjectivity, and objectivity proportions.

Sentiment polarity is typically a numeric score that’s assigned to both the positive and negative aspects of a text document based on subjective parameters like specific words and phrases expressing feelings and emotion. Neutral sentiment typically has 0 polarity since it does not express and specific sentiment, positive sentiment will have polarity > 0, and negative < 0. Of course, you can always change these thresholds based on the type of text you are dealing with; there are no hard constraints on this.

we focus on trying to analyze a large corpus of movie reviews and derive the sentiment. We would cover a two varieties of techniques for analyzing sentiment, which include the following.

Unsupervised lexicon-based models
Traditional supervised Machine Learning models
The main objective in this Project is to predict the sentiment for a number of movie reviews obtained from the Internet Movie Database (IMDb). This dataset contains 50,000 movie reviews that have been pre-labeled with “positive” and “negative” sentiment class labels based on the review content. Besides this, there are additional movie reviews that are unlabeled.

The dataset can be obtained from http://ai.stanford.edu/~amaas/data/sentiment/ , courtesy of Stanford University and Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts.

Hence our task will be to predict the sentiment of 15,000 labeled movie reviews and use the remaining 35,000 reviews for training our supervised models.
