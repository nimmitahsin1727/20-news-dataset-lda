# 20-news-dataset

This project is mainly focused on 
- Reading raw data from folders.
- Pre-process data:
  - Remove numbers. ✅
  - Convert word into lowercase word. ✅
  - Remove all stop words. ✅
  - Remove all punctuations. ✅
  - Some white spaces may be added to the list of words, due to the translate function & nature of our documents. Remove them as well. ✅
  - Remove just-numeric strings. ✅
  - Lemmatizer:
   minimizes text ambiguity. ✅
  - Remove words with only 2 characters or less. [Low frequency] ✅
  - Remove words with more than 12 characters. [High frequency] ✅
- Store those pre-process data into csv files both training and testing.
- Bag of WORDS: TF-IDF Vectorizer.