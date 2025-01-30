# sentimentanalysis-fb (Group named Anti-Feminist Community)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11A2e66LCMluQJ-rAI0DigV00FItf0E6w#scrollTo=CWJD9YnGg_8I&uniqifier=1)

This project performs sentiment analysis on Facebook group named Anti-Feminist Community posts to determine whether posts exhibit negative or positive sentiment. I

## Features
- **Data Preprocessing:**
  - Load Facebook group post data
  - Select relevant columns
  - Handle missing values
- **Translation:**
  - Detect Bangla text
  - Translate Bangla posts into English using Google Translator API
- **Sentiment Analysis:**
  - Use `distilbert-base-uncased-finetuned-sst-2-english` from Hugging Face
  - Tokenize and truncate text for processing
  - Classify sentiment as `POSITIVE` or `NEGATIVE`
- **Data Visualization:**
  - Sentiment distribution count plot
  - Average likes and shares per sentiment
  - Sentiment trends over time
  - Sentiment heatmap by day of the week
  - Word cloud for negative sentiment posts

