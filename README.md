# Emotion_Recognition
Emotion Detection from Text data. 
Load necessary packages and libraries.
Data Agumention and Organization: Use data from multiple sources and combine them with proper organisation to increase size of data. Split data into train and test sets.
EDA & Data Visualization: Analyze, Understand and Explore the Data.
Preprocessing:
(NLP -> Text Cleaning + Text Vectorization)
Text cleaning: Remove emojis, Convert Emoticons to Words, Apply Text Contractions, Correct Abbreviations, Remove Mentions and URLs, Remove Special Characters, Punctuations, HTML tags, Escape Characters and Extra Spaces, Apply Spell Check, Lemmatize/Stem texts.
Text Vectorization: Convert text data to numerical vectors. (I wil use Tfidf vectorization technique, but other methods like Bag of Words or Word embedding can also be used.)
Label Encoding: Machine Learning models can not understand text labelled categories hence we must convert text labels to numerical values before feeding our data to a ML model.
Training: Feed processed data to various Machine Learning/Deep Learning models and Test each model's accuracy using Test data (created during train-test-split).
Create Pipeline: Choose the best performing model and create a model pipeline.
Ground Testing: Use the trained model to predict language from user inputs.
