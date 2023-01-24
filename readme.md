# Generative-Discriminative-Chatbot

This project focuses on text generation (language modeling). We chose Yelp reviews as our corpus and wish to generate positive reviews for restaurants, markets, etc. This task can be applied to real life. The challenges mainly come from 2 perspectives: 1) Yelp reviews include many initials/shortcuts/slangs such that the corpus contains many rare words; 2) Yelp reviews contain many uncommon punctuation combinations, so the raw data need to be cleaned with care at the beginning.
To accomplish this project, we applied both Long short-term memory (LSTM) and Markov Chain (MM) models, which are discriminative and generative respectively. We first preprocessed the text in the corpus. Then we trained both models based on the text and used the models to generate texts. In addition, we analyzed and evaluated the results quantitatively and qualitatively. Finally, we discussed the pros and cons of the two methods from multiple perspectives.


Python version: 3.9

Modules need to intall: spacy, keras, tensorflow, pickle, markovify, datasets

Dataset link: https://www.kaggle.com/datasets/yacharki/yelp-reviews-for-sa-finegrained-5-classes-csv
