# Sentiment Analysis of Customer Reviews

**Oasis Infobyte – Data Analytics Internship**

## Project Overview

This project analyses customer reviews from the Amazon Fine Food Reviews dataset using Python and Natural Language Processing (NLP). The VADER sentiment analysis model is used to classify reviews as Positive, Negative or Neutral.

## Dataset

- Dataset: Amazon Fine Food Reviews
- Source: Kaggle
- Sample size: 10,000 reviews
- Missing review texts after cleaning: 0

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- NLTK (VADER)
- WordCloud

## Project Workflow

1. Dataset loading and exploration
2. Text preprocessing
3. VADER sentiment classification
4. Sentiment distribution visualisation
5. Comparison with customer ratings
6. Positive and negative word clouds
7. Final analysis and conclusions

## Results

| Metric | Result |
|---|---:|
| Total reviews | 10,000 |
| Positive sentiment | 87.98% |
| Neutral sentiment | 2.03% |
| Negative sentiment | 9.99% |
| Agreement with rating-based sentiment | 80.50% |
| Average customer rating | 4.20 / 5 |

## Conclusion

The analysis found that positive sentiment dominated the selected customer reviews. VADER predictions agreed with rating-derived sentiment categories for 80.50% of reviews.

The project demonstrates how NLP techniques can help analyse customer opinions, while highlighting the limitations of lexicon-based sentiment classification.

## Dataset Source

[Amazon Fine Food Reviews – Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
