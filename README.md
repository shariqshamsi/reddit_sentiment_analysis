# Reddit Sentiment Analysis

## Overview
This project is designed to fetch and analyze sentiment in Reddit comments using Python. The sentiment scores are generated using OpenAI's GPT models, and the data is visualized with Seaborn and Matplotlib. The processed comments and their corresponding sentiment scores are saved in a CSV file for further analysis.

## Features
- Fetch Reddit comments using the Reddit API.
- Analyze sentiment with OpenAI's GPT models.
- Visualize sentiment data using Seaborn and Matplotlib.
- Export comments and sentiment scores to a CSV file.
- Secure API keys and sensitive data using a `.env` file.

## Dependencies
The following libraries are used in this project:
- `openai`: To interact with OpenAI's GPT models for sentiment analysis.
- `praw`: To fetch Reddit comments using the Reddit API.
- `pandas`: For data manipulation and exporting data to CSV.
- `seaborn`: For creating visualizations of the sentiment data.
- `matplotlib`: For plotting the data.
- `python-dotenv`: To load environment variables from a `.env` file.
