# 📊 Wiki Articles Text Analysis

This project explores a dataset of Wikipedia articles using natural language processing (NLP) techniques, text mining, and visualization tools. The analysis uncovers key insights such as article length distributions, most frequent words, topic modeling, and sentiment analysis.

## 📂 Project Structure
- **`data/`**: Contains the dataset (`wiki-articles.json`).
- **`notebooks/`**: Includes the main analysis notebook (`wiki_text_analysis.ipynb`).
- **`README.md`**: This document provides an overview of the project.
- **`requirements.txt`**: Python dependencies required for the project.

## 🔍 Analysis Overview
### 1. Distribution of Article Lengths
- Explored the distribution of article lengths with statistical measures (mean, median, etc.).
- **Visualization**: Histogram and density plot of article lengths.

### 2. Most Frequent Words
- Extracted top keywords using TF-IDF and visualized them with bar plots and word clouds.

### 3. Rare Character Analysis
- Analyzed the frequency of rare characters ('x', 'z', 'j', 'q') in the articles.

### 4. Topic Modeling
- Used Latent Dirichlet Allocation (LDA) to identify 5 key topics in the dataset.
- **Visualization**: Bar plot showing topic importance.

### 5. Sentiment Analysis
- Performed sentiment polarity and subjectivity analysis on the articles.
- **Visualization**: Scatter plot and histograms of sentiment polarity and subjectivity.

### 6. Token and Word Length Analysis
- Analyzed token lengths and average word lengths across the articles.
- **Visualization**: Distribution plots for token lengths and word lengths.

### 7. Lexical Diversity
- Measured the lexical diversity of articles to determine their linguistic variety.

## 🚀 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Wiki-Articles-Text-Analysis.git
   cd Wiki-Articles-Text-Analysis
