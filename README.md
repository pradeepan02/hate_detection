## Overview

This project involves implementing and evaluating machine learning algorithms using two CSV files related to social media data. The goal is to classify tweets based on their content and evaluate various machine learning models.

## Data Files

1. **train.csv**: This file contains training data with tweet IDs, labels, and the tweet text.
   - **Columns**:
     - `id`: Unique identifier for the tweet
     - `label`: Classification label for the tweet
     - `tweet`: Text of the tweet

2. **twitter_data.csv**: This file contains additional data with various features related to tweets and their classification.
   - **Columns**:
     - `count`: Count of tokens or words in the tweet
     - `hate_speech`: Binary indicator for hate speech
     - `offensive_language`: Binary indicator for offensive language
     - `neither`: Binary indicator for neither hate speech nor offensive language
     - `class`: Class label for the tweet (e.g., hate speech, offensive language, neither)
     - `tweet`: Text of the tweet
