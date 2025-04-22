# sentiment-diary

This project gives you a tool that processes your daily journal entries, analyzes the sentiment of each entry, and visualizes the most frequent emotional words through a **Word Cloud**. Thanks to it, you get a quick overview of the emotions you’ve experienced over a period of time.

## Features

- **Sentiment Analysis**: Uses a pre-trained Hugging Face sentiment model to classify journal entries as **positive**, **negative**, or **neutral**.
- **Word Cloud Generation**: A word cloud is generated based on the most frequently used words in your journal entries. It mainly focuses on emotional words.
- **Stopwords Removal**: You get rid of common stopwords,so you only have relevant emotional terms appear in the word cloud.
- **Visual Customization**: You can customize the word cloud’s appearance, including its size, color scheme, and font size.

## How It Works

1. **Input Journal Entries**: Provide your journal entries as a list of dictionaries, each containing a date and the journal entry text.
2. **Sentiment Analysis**: The sentiment of each entry is analyzed and categorized into three categories.
3. **Word Cloud Creation**: After sentiment analysis, the emotional words are extracted, and a word cloud is generated.
4. **Visualization**: The word cloud is displayed and saved as an image file.

Read my Medium writing on this project for further understanding: https://medium.com/@busraracoban/visualizing-your-emotions-building-an-ai-powered-mood-word-cloud-from-your-journal-23f6805cb092 

## Installation

To use the Emotional Journal Analyzer, make sure you have the following dependencies installed:

- `transformers` - for sentiment analysis using Hugging Face
- `nltk` - for text processing (including stopword removal)
- `matplotlib` - for plotting the word cloud
- `wordcloud` - for generating the word cloud
- `pandas` - for handling journal entries in a structured format

You can install all required libraries using pip:

```bash
pip install transformers nltk matplotlib wordcloud pandas
