# Yelp Review Sentiment Analysis Using Transformers

This project aims to scrape reviews from Yelp, process the reviews using a pre-trained BERT-based model from HuggingFace, and perform sentiment analysis on the reviews.

## Project Overview
The project uses the `nlptown/bert-base-multilingual-uncased-sentiment` model from HuggingFace to classify reviews into sentiment scores ranging from 1 to 5. Here's the general flow:
1. Scraping reviews from a Yelp page.
2. Encoding reviews using the BERT tokenizer.
3. Using the BERT model for sentiment analysis.
4. Storing the results in a pandas DataFrame.

## Setup Instructions

### Prerequisites
- Python 3.8+
- PyTorch
- HuggingFace Transformers
- BeautifulSoup4
- Requests
- Pandas

### Installation
Clone the repository:
```bash
git clone https://github.com/your-username/yelp-review-sentiment-analysis.git
cd yelp-review-sentiment-analysis
