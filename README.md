# 20-news-dataset

## About
This project is mainly focused on:
- Reading raw data from folders [comp.graphics, rec.motorcycles, talk.politics.guns].
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

## Packages

- glob
- re
- numpy
- pandas
- matplotlib
- nltk
- sklearn

## Folder structure
```bash
├── 20_news_data.ipynb
├── data
│   ├── 20news-bydate-train
│   │   ├── comp.graphics
│   │       ├── ...
│   │   ├── rec.motorcycles
│   │       ├── ...
│   │   └── talk.politics.guns
│   │       ├── ...
│   └── 20news-bydate-test
│       ├── comp.graphics
│           ├── ...
│       ├── rec.motorcycles
│          ├── ...
│       └── talk.politics.guns
│           ├── ...
├── training_df.csv
├── testing_df.csv
├── README.md
└── .gitignore
```
