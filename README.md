# BrainCap - Ubottu
BrainStation 2023/24 Capstone Project
- The dataset for this project was taken from Kaggle and is known as the Ubuntu Dialogue Corpus
- Direct link to this dataset : https://www.kaggle.com/datasets/rtatman/ubuntu-dialogue-corpus/data
# Project Overview
The Purpose of this project is to create a chatbot. In order to first create one we will need to do some analysis and analytics on the dialogue corpus for us to first understand the text and then go from there
# Areas of Interest
Text Analysis is hugely popular with the amount of people and data available. By even transcripting audio, the data can grow in folds. This will help us understand our product much better 
# Problem Area
Millions of questions , but limited answers and wait time. When we have a question, we have to wait for someone to reply. In this modern world, we need answers instantly
# Data Science Solution
The aim of this project is to use Natural Language Processing(NLP) Models, Python Interface, Machine and Deep Learning to analyse the data and detect patters and trends within them to understand the problems and benefits the product offers
# Impact of Solution
Huge Impact on customer service and greater trust in product. Reduced wait times as the most important and frequent questions have alredy been asked
# Description of DataSet
The dataset consists of almost one million two-person conversations extracted from the Ubuntu chat logs, used to receive technical support for various Ubuntu-related problems. The conversations are all text based and answered via a forum from different usernames. This is a heavy dataset broken down into 3 .csv files. The size of all the files combined is about 3GB.
- dialogue_texts contain about 1038325 lines - 11035331 words & 116070597 characters - Our Main Focus as of now
- diaglogue_texts_196 contain about 9212878 lines - 91660344 words & 996253904 characters
- diagoue_texts_301 contain about 16587831 lines - 166392849 words & 1799936480 characters
# Data Dictionary
- Folder - The folder the query was retrieved from
- dialogueID - ID that a set of text corpus is part of
- Date - Timestamp when query was submitted
- From - The user who sent the query
- To - The user whom the answer is for
- Text - The line of text that is going to help our analysis. The question and response
# Table of Contents
- Introduction
- Explanatory Data Analysis
- Data Cleaning
- Preprocessing
  - Removing Digits
  - Removing Punctuation
  - Lemmatizing Text
  - Lowercasing
  - Removing Stopwords
  - Tokenizing
  - Counting Words & Characters
  - Parts of Speech
- Baseline Modeling
   - Count Vectorizer
   - Word2Vec
   - K-Means
   - Latent Dirichlet Allocation
     - Topic Modelling 
   - Principal Component Analysis
     - Vector Embeddings
 - Advanced Modelling
   - Assigning Values
   - Bidirectional Encoder Representation from Transformers
   - Knowledge Mapping via Spacy
- Conclusion
# Addtional Comments/Thoughts
Dec 23' - Currently am working on EDA and slides. Once a notebook is completed, it will be added on to the repositry and this section will be updated on the next portion being worked on. A copy of a notebook to be posted, so can follow my own chain of thoughts

Feb 24' - After a while was able to work back on this and added BERT and Knowledge Mapping via Spacy NLP Models.<br>
In addition to it , carried out Topic Modelling via LDA and vector embeddings on PCA.

** Note : Unfortunately due to working on laptop, i wasnt able to process as much computational power wise, and only ran the pre-trained models on a subset of 500-1000 rows. Epoch Loss was low. 
# Citation
Ryan Lowe, Nissan Pow, Iulian V. Serban and Joelle Pineau, "The Ubuntu Dialogue Corpus: A Large Dataset for Research in Unstructured Multi-Turn Dialogue Systems", SIGDial 2015. URL: http://www.sigdial.org/workshops/conference16/proceedings/pdf/SIGDIAL40.pdf
