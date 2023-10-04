                                                                        Deep Convolution Neural Networks For Twitter Sentiment Analysis

This project focuses on sentiment analysis using Convolutional Neural Networks (CNNs) on Twitter data. Sentiment analysis is crucial for understanding public opinions and emotions expressed on social media platforms. Leveraging pre-trained word embeddings from GloVe, the project aims to predict sentiments in tweets, classifying them as positive or negative.

Key Features
Data Pre-processing: Extensive preprocessing is applied to Twitter data, handling issues such as misspelled words, emoticons, URLs, and more.

Feature Extraction: The project extracts unigrams and bigrams from the dataset, creating a frequency distribution to identify key features for sentiment analysis.

CNN Architectures: Various CNN architectures are implemented, ranging from single to multiple convolutional layers, allowing for a comparative analysis of their performance.

Sparse and Dense Vector Representations: The tweets are represented as feature vectors, employing sparse vector representation for unigrams and bigrams, as well as a dense vector representation using a vocabulary of the top 90,000 words.


Implementation
The project is implemented using Keras with a Tensor Flow backend. Different CNN architectures are explored and compared, providing insights into the impact of network depth on sentiment prediction.

Results
The provided tweets encompassed a diverse mix of words, emoticons, URLs, hashtags, user mentions, and symbols. Prior to algorithm training, a comprehensive pre-processing step was applied to make the tweets suitable for model input. The project employs a Convolutional Neural Network (CNN) for sentiment classification on Twitter data.

Conclusion
The CNN with four convolutional layers emerged as the most effective in capturing intricate patterns and nuances in sentiment expression.
