# YouTube_Comment_Classifier

### Problem Statement
The owner of a YouTube channel seeks to understand and manage audience sentiment and the nature of feedback regarding their latest videos. They receive numerous comments and desire an automated solution to classify these comments into categories such as toxic, obscene, insulting, or non-toxic. By employing machine learning models, this solution aims to quickly categorize viewer feedback, providing the channel owner with insights into the nature of audience interactions. This classification will help identify and address harmful or inappropriate content, enhance community management, and refine the content strategy to foster a positive and engaging viewer environment.

### Workflow
Users need to enter either their YouTube url or any comments in the input section. If users has entered,our platform will web scrap the comments in their YouTube url video. Based on the nature of the comments , our model will predict the probability of comment being toxic, obscene and insult. If the probability is quite low, we consider it as non toxic comment. In the classification column, our platform will classify whether the comments are positive, negative or neutral.
<img width="761" alt="Screenshot 2024-05-30 at 4 55 23 PM" src="https://github.com/Ugyen00/YouTube-Comment-Classifier/assets/115082366/2f74484a-d18a-4f66-ab18-b265e193d667">
<img width="716" alt="Screenshot 2024-05-30 at 4 55 54 PM" src="https://github.com/Ugyen00/YouTube-Comment-Classifier/assets/115082366/e5148155-7d47-4fa0-a0ab-850a2968f211">

### Libararies that need to be imported
#### import pandas as pd
#### import matplotlib.pyplot as plt
#### import nltk
#### from nltk import WordNetLemmatizer
#### from nltk import pos_tag, word_tokenize
#### from nltk.corpus import stopwords as nltk_stopwords
#### from nltk.corpus import wordnet
#### from sklearn.feature_extraction.text import TfidfVectorizer
#### from sklearn.model_selection import train_test_split
#### from sklearn.svm import SVC
#### from sklearn.metrics import f1_score, confusion_matrix
#### import re

### Downloaad NLTK resources
#### nltk.download('punkt')
#### nltk.download('omw-1.4')
#### nltk.download('wordnet')
#### nltk.download('stopwords')
#### nltk.download('averaged_perceptron_tagger')
