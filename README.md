# Sentiment-Analysis-using-Conventional-rule-based-approach-vs-Hugging-Face-Pretrained-Transformers-RoBERTa

Sentiment Analysis is used to determine the feelings or sentiments expressed in texts. It is an NLP technique that allows you to understand the nuances in human texts and to determine if data is either positive, negative or neutral. There are currently several conventional rule-based approaches to sentiment analysis and in this project, we have identified the well-known VADER model (Valence aware dictionary and sentiment reasoner). VADER model is a very efficient rule-based sentiment analyzer that employs a "bag of words" approach, but it has a drawback in the sense that VADER neglects to take into consideration the relationships between words and so it ignores the context behind words (with context being crucial in human speech). This brings up the project's main point of interest. We utilize a pretrained model called RoBERTa to classify our data and return the sentiment of the fed data. This model, which is a sophisticated transformer model uses deep learning in the form of pretraining and examines the context behind human speech or sentences. The dataset will first undergo basic exploratory data analysis (EDA) in order to get insights and findings from it. To better explain the method, we will use a sample news headline and perform some simple analysis on the parsed information using the Python Natural Language Toolkit (NLTK).
Our project's main objective is to compare the sentiment prediction of the conventional rule-based approach to the adopted pretrained model.
