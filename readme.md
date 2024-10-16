# Extraction and Analysis of Individuals and Firms in News Articles


This project focuses on extracting and analyzing the names of individuals mentioned in news articles using advanced Natural Language Processing (NLP) techniques. By processing vast collections of articles, the goal is to generate insights on key persons frequently mentioned over time, their contexts, and how their appearances evolve across different articles and time periods.

![Process Overview](./assets/extraction_demo.gif)


## Introduction

In the modern world of news and information, understanding the influence and frequency of specific individuals in media can provide powerful insights into current events and public discourse. This project leverages NLP to extract names of people or firm mentioned in news articles, providing a clear picture of **who** is being talked about, **when**, and **in what context**.

Using `spaCy` for entity recognition and Python for data manipulation and visualization, the system can process hundreds of articles, extract key mentions, and output visual analyses that show trends, article-by-article breakdowns, and frequency distributions of names.

## Key Features

- **Automated Person Name Extraction**: Extracts mentions of individuals from large news article datasets using NLP.
- **Article Metadata Integration**: Merges extracted person data with article metadata like publication date, author, and source.
- **Temporal Analysis**: Tracks the appearance and frequency of persons across a time range.
- **Contextual Insights**: Links extracted names to surrounding text to understand context.
- **Visual Reporting**: Generates detailed visualizations of person mentions over time.

## Installation and Setup

### Prerequisites

- Python 3.7 or higher
- Basic knowledge of Python, NLP, and data analysis
- Necessary libraries: `spaCy`, `pandas`, `matplotlib`, `tqdm`

### Setup Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/news-person-extraction.git
   cd news-person-extraction
