# Data Cleaning and Preparation Project

This project involves reading, analyzing, and processing a dataset of text files. The main tasks include:

- Tokenizing text files into words and sentences.
- Generating word clouds to visualize word frequency.
- Calculating word frequencies and plotting them.
- Performing sentiment analysis on the text data.

## Prerequisites

Ensure you have the following packages installed:
- `os`
- `random`
- `re`
- `collections`
- `nltk`
- `wordcloud`
- `matplotlib`

Install the necessary packages using pip:

```bash
pip install nltk wordcloud matplotlib
```

## Setup

Download the necessary NLTK data:

```python
nltk.download('stopwords')
nltk.download('vader_lexicon')
nltk.download('gutenberg')
```

## Directory Structure

Ensure your directory structure is as follows:

```
/content/drive/MyDrive/nlp_surya/dataset
```

Place all text files to be analyzed inside the `dataset` directory.

## Steps

1. **List and Count Files**: Read the dataset directory and list all files. Verify the number of files.
2. **Read a Random File**: Select a random file from the dataset and read its contents.
3. **Calculate Average Number of Words per Sentence**: Analyze each file to calculate the average number of words per sentence and the number of paragraphs.
4. **Generate a Word Cloud**: Create a word cloud for a selected file to visualize the frequency of words.
5. **Word Frequency Distribution**: Clean the text and calculate word frequencies, then plot the most common words.
6. **Sentiment Analysis**: Perform sentiment analysis on the text data and calculate average sentiment scores.
7. **Find Sentences with Most Common Word**: Identify sentences containing the most common word in the text.

## Results

After running the analysis, you will obtain:
- Word clouds visualizing word frequencies.
- Frequency distribution plots of the most common words.
- Sentiment scores indicating the average positive, negative, neutral, and compound sentiments.
- Sentences containing the most frequently occurring words.


