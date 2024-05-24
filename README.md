# Sentimental-Analysis-on-Product-Reviews-using-Deep-Learning
**INTRODUCTION**

The idea introduces an automated sentiment analysis framework tailored for E-commerce datasets. Leveraging a combination of Convolution Neural Networks(CNN) and Bidirectional Long Short-Term Memory networks(BiLSTM), the proposed model employs heuristic-based techniques to enhance the accuracy of sentiment classification.
The integration of CNN facilitates effective feature extraction from textual data, while BILSTM captures contextual dependencies and sequential patterns. 
The heuristic approach fine-tunes the model by incorporating domain specific knowledge, optimizing its performance for sentiment analysis in the context of E- commerce. 
Experimental evaluations on relevant datasets demonstrate the effectiveness of the proposed methodology in accurately discerning sentiments expressed in E- commerce reviews. The pre-processing steps for the input E-Commerce data are blank space removal, stop word removal, and stemming. 
Also, the word2vec features are also extracted. The method called “CNN with BiLSTM” is separately used which is named as OH-CNN-BiLSTM that performs the hybridization of two models for the sentimental analysis. 
The main idea used in this work is to develop an improved Galactic Swarm Optimization(IGSO) algorithm for improving the hybridized model, as it provides faster convergence and also solves optimization issues. 
The results highlight the potential of the CNN- BiLSTM model with heuristic enhancements as a robust tool for automated sentiment analysis in the dynamic and nuanced domain of E-commerce.

**DATASET DETAILS**

Dataset	1:	(“Online	Product	reviews”):	The	website https://www.kaggle.com/aaroha33/e-commerce-sentiment- analysis/data is where the input data for the recommended method is obtained. Reviews from thousands of products are included in this dataset which includes the products reviews and sentiment labels.
Dataset 2: (“Amazon Reviews for Sentiment Analysis”) The website https://www.kaggle.com/datasets/tarkkaanko/amazon is where the data’s are collected. The dataset has 5000 rows and 11 columns which includes reviews and their ratings out of 5.

**PRE - PROCESSING**

Text Cleaning: The data is cleaned to remove any irrelevant or noisy information's like removing special characters, punctuation and non – alphabetic characters. 

Stopword Removal: Stopwords are common words that do not carry much meaning and can be safely removed from the text. Example: “the”, “is”, “and”, etc. 

Normalization: Normalization is the process of transforming words to their base or root form. This step helps in reducing the number of unique words and treating different forms of the same word as a single entity.

**WORD2VECTOR FEATURES**

The Word2Vec method is a neural network-based approach that learns word embeddings, which are dense vector representations of words.

These word embeddings capture semantic and syntactic relationships between words based on their context in a given corpus.

Finally, the extracted features from words are converted to vector formation

**EXTRACTING FEATURES**

The pre–processed data is then extracted into Positive, Negative, and Neutral using VADER method. VADER, which stands for Valence Aware Dictionary for Sentiment Reasoning, this is a pre – built sentiment analysis tool designed for analyzing the sentiment of the text data.

**HYPERPARAMETER OPTIMIZATION USING IGSO**

The IGSO algorithm’s primary goal is to deliver accurate solutions and faster convergence across a broad range of dimensional spaces. 
It is an optimization algorithm inspired by the motion of stars, galaxies and superclusters of galaxies under the influence of gravity.

**MODEL CONSTRUCTION**

The optimized data are integrated for subjecting it into the classification phase.

The optimized training model undergoes classification phase where hybrid algorithm is used.
 
The hybrid algorithm named OH – CNN – BiLSTM, which is developed by optimizing certain parameters in CNN and Bi – LSTM using the developed IGSO for enhancing classification performance. 

At last, the reviews are classified as Positive or Negative.

**REFERENCES**

Dr. N. Ramshankar, Dr. Joe Prathap P. M., “Automated sentimental analysis using heuristic-based CNN-BiLSTM for E-commerce dataset”, Data & Knowledge Engineering, Elseiver(2023).

P Rakshit, PK Srivastava, M Afjal, SK. Srivastava, Sentimental analytics on Indian big billion day of flip kart and amazon, SN Computer Science(2021), https://doi.org/10.1007/s42979-020-00441-3.









