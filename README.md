

# Sentiment Analysis in Climate-Centric Energy Solutions

## Introduction
This project explores the application of sentiment analysis to gauge public opinion regarding new energy solutions designed to combat climate change. By analyzing public comments and discussions, the project provides insights into how people feel about climate-focused innovations, which can inform policy decisions, business strategies, and advocacy efforts.

## Project Motivation
The transition to sustainable energy solutions is a global priority, and understanding public sentiment is essential for driving this change effectively. Sentiment analysis helps identify public support, concerns, and resistance, allowing stakeholders to adapt their messaging and strategies for better engagement and smoother adoption of new technologies.

## Methodology

### Data Collection
We used the YouTube API to extract comments from popular news outlets like BBC, Fox, and CNN, gathering feedback on climate-related energy innovations. This data was the foundation for our sentiment analysis.

### Data Preprocessing
Before analyzing sentiment, the raw text data underwent several preprocessing steps:
- **Language Filtering**: Focusing on English comments only.
- **Text Standardization**: Converting text to lowercase, applying lemmatization, and removing irrelevant content such as URLs and HTML tags.
- **Emoji & Spelling Correction**: Emojis were converted to text, and spelling corrections were made to ensure clarity.

### Sentiment Analysis
Three tools were used to perform sentiment analysis:
- **VADER**: Captures sentiment intensity and nuances.
- **TextBlob**: Provides a polarity score for quick analysis.
- **Pattern**: Offers deeper insights by analyzing the text's syntactic structure.

By using multiple methods, we achieved a well-rounded view of public sentiment, allowing us to compare results and enhance the reliability of our findings.

## Visualizations
The results were visualized through various charts and plots, including:
- **Sentiment Distribution**: Illustrates the proportion of positive, negative, and neutral sentiments.
- **Word Cloud**: Displays frequently occurring terms in relation to sentiments.
- **Sentiment Correlation Heatmap**: Shows how different sentiments correlate with each other across topics.
- **T-SNE Embeddings**: Provides a 2D visualization of word embeddings to highlight how sentiment-related terms cluster together.

## Final Report
[Project Report (PDF)](https://github.com/JasmineBorse/NLP_Project/blob/main/NLP_Project_Analysis_Final.pdf)


## Conclusion
This project highlighted public attitudes towards climate-related energy solutions, offering critical insights for shaping future policies and strategies. By continuously monitoring sentiment, stakeholders can respond proactively to shifting public opinions and foster greater alignment in the global push toward sustainable energy.

