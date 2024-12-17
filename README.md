# Sentiment Analysis of Google Play Store Reviews for Functional Requirement Extraction

## Overview

This project demonstrates how to use sentiment analysis on Google Play Store reviews to identify important features and functional requirements for app development. By analyzing reviews from five different apps, we aim to determine which features users value the most and what improvements they seek. This analysis provides actionable insights for creating a new app tailored to user needs.

## Features

- **Data Collection**: Scraping Google Play Store reviews for multiple apps using automated tools.
- **Sentiment Analysis**: Using Python libraries to classify reviews as positive, negative, or neutral.
- **Feature Extraction**: Identifying recurring themes and features from reviews.
- **Functional Requirement Generation**: Translating user feedback into actionable app requirements.

## Project Workflow

1. **Data Scraping**: Collect reviews and ratings for five apps from the Google Play Store.
2. **Data Cleaning**: Preprocess and clean the review data for analysis.
3. **Sentiment Analysis**:
   - Perform sentiment analysis using Python libraries like `TextBlob` or `VADER`.
   - Categorize reviews based on user sentiment (positive, neutral, negative).
4. **Feature Analysis**:
   - Extract common themes and features mentioned in reviews.
   - Quantify the sentiment around each feature.
5. **Requirement Derivation**:
   - Identify critical features users want.
   - Create functional requirements for a new app based on user feedback.

## Tools and Libraries

- **Web Scraping**: `google_play_scraper`
- **Data Analysis**: `pandas`, `numpy`
- **Sentiment Analysis**: `TextBlob`, `NLTK`, `VADER`, `transformers`
- - **Text Processing**: `demoji`, `unidecode`, `num2words`, `nltk`
- **Visualization**: `plotly-express`

## Results

The project highlights:
- Which app features users appreciate the most.
- Areas where existing apps fall short, based on negative reviews.
- A list of functional requirements derived from user feedback for developing a new app.

## Installation and Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/arjunKa/SentimentAnalysis.git
