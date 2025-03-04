# VibeCheck
VibeCheck is a machine learning-powered tool designed to analyze YouTube video comments. It extracts comments using the YouTube API, cleans them, performs sentiment analysis, and classifies them into topics using NLP techniques. The system adjusts sentiment classification based on the video's context, making it more insightful for content creators.

## Features
- YouTube Comment Extraction: Fetches comments using the YouTube API.
- Text Preprocessing: Cleans and processes text (removes URLs, emojis, punctuation, and stopwords).
- Sentiment Analysis: Utilizes BERT and VADER models to classify comments as Positive, Negative, or Neutral.
- Context-Aware Adjustments: Adjusts sentiment scores based on video-related keywords.
- Topic Extraction: Uses Latent Dirichlet Allocation (LDA) to identify discussion topics.
- Data Export: Saves processed comments along with their analysis in a CSV file.
## Technologies Used:
- Python
- Google YouTube API
- NLTK (Stopword removal, Tokenization, Lemmatization)
- VADER (Sentiment Analysis)
- BERT (Sentiment Classification)
- Scikit-Learn (for topic modeling)
