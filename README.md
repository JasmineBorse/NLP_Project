

# Sentiment Analysis in Climate-Centric Energy Solutions

## Overview
This project focuses on applying sentiment analysis to understand public opinion regarding innovative energy solutions aimed at addressing climate change. By analyzing public comments from online discussions, the project aims to provide valuable insights into how people perceive climate-focused initiatives, which can guide policy-making, business strategies, and advocacy campaigns.

## Motivation
The global shift toward sustainable energy solutions is imperative, and gauging public sentiment is crucial for ensuring successful transitions. Sentiment analysis helps identify the level of public support, concerns, or resistance, allowing key stakeholders to adjust their communication and strategy to foster broader acceptance and smoother adoption of these technologies.

## Approach

### Data Collection
We employed the YouTube API to extract public comments from leading news channels, including BBC, Fox, and CNN, focusing on discussions around climate and energy innovations. These comments form the core dataset for sentiment analysis.

### Data Preparation
The collected text data was processed through several steps to ensure it was clean and suitable for analysis:
- **Language Filtering**: Restricting the dataset to English comments.
- **Text Cleaning**: Standardizing the text by converting to lowercase, lemmatization, and removing unnecessary elements such as URLs, HTML tags, and special characters.
- **Emoji & Spelling Handling**: Converting emojis to text equivalents and correcting common spelling errors for better analysis.

### Sentiment Analysis Methods
We employed three popular sentiment analysis tools to ensure comprehensive insights:
- **VADER**: Captures sentiment intensity with fine granularity.
- **TextBlob**: Provides a basic polarity score for general sentiment classification.
- **Pattern**: Delivers in-depth syntactic analysis to enhance sentiment understanding.

Using multiple approaches allowed us to cross-validate results and strengthen the accuracy of the sentiment classifications.

## Data Visualization
The insights from sentiment analysis were visualized using several types of graphs:
- **Sentiment Breakdown**: Displays the ratio of positive, negative, and neutral sentiments.
- **Word Cloud**: Highlights common terms associated with specific sentiments.
- **Correlation Heatmap**: Shows how different sentiments relate to each other across various discussions.
- **T-SNE Plot**: A 2D representation of word embeddings, revealing clusters of sentiment-related words.

## Detailed Report
For a complete overview of our findings, check out the final report:  
[Project Report (PDF)](https://github.com/JasmineBorse/NLP_Project/blob/main/NLP_Project_Analysis_Final.pdf)

## Conclusion
The project underscores the importance of understanding public sentiment regarding climate-related energy innovations. The insights derived can help inform more effective communication and strategy for both policymakers and industry players, aiding in the global move towards sustainable energy solutions.

