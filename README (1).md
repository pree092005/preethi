# Decoding Emotions Through Sentiment Analysis of Social Media Conversations

This project analyzes public social media conversations (tweets) to detect *sentiment* (positive, negative, neutral) and classify *emotions* (joy, anger, sadness, fear, etc.) using AI-powered Natural Language Processing (NLP) models.

## Features

- Scrapes live tweets from Twitter using a keyword or hashtag
- Performs sentiment analysis using the VADER algorithm
- Classifies emotions using a pre-trained transformer model from Hugging Face
- Displays and exports the results to a CSV file
- Can be extended for dashboards or real-time monitoring

---

## How It Works

1. *Fetch Tweets:* Uses snscrape to collect real-time tweets based on a keyword or hashtag.
2. *Sentiment Analysis:* Uses VADER to evaluate polarity (positive, negative, neutral).
3. *Emotion Detection:* Uses DistilRoBERTa transformer model to classify emotions.
4. *Output:* Results are displayed in the terminal and saved as a CSV file.

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/emotion-sentiment-analysis.git
cd emotion-sentiment-analysis
