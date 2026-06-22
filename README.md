# Climate News Analysis: Do News Outlets Link Extreme Weather to Climate Change?
## Overview

This project investigates how major news organizations frame the relationship between extreme weather events and climate change.

Using 221 weather-related news video transcripts collected from eight news organizations, we applied natural language processing (NLP) and text mining techniques to analyze climate attribution, topic structure, and sentiment across media outlets.

## Research Questions 
1. How frequently do news outlets connect extreme weather events to climate change?
2. How does climate change framing vary across major news organizations?

## Dataset
- 221 weather-related news video transcripts
- Source: YouTube news dataset
- 8 news organizations:
  - CNN
  - Fox News
  - MSNBC
  - NBC News
  - ABC News
  - CBS News
  - NewsNation
  - Sky News Australia

## Methodology
### Text Preprocessing
- Tokenization
- Stopword removal
- Lemmatization
- Text cleaning

### NLP Analysis
#### TF-IDF Analysis
Identified vocabulary that was most distinctive for each news outlet.
#### Climate Attribution Scoring
Created a climate attribution score based on the co-occurrence of climate-related and weather-related keywords.
Attribution Score = Climate Hits × Weather Hits
#### Topic Modeling
Applied Latent Dirichlet Allocation (LDA) and selected K = 6 topics using perplexity analysis.
#### Sentiment Analysis
Used sentimentr in R to evaluate emotional tone and examine relationships between sentiment and climate attribution.

## Key Findings 
### Climate Attribution
- NBC News showed the highest mean climate attribution score.
- Sky News Australia ranked second.
- MSNBC had the highest percentage of climate-attributed articles.
- CNN showed no explicit climate attribution in the sampled transcripts.

### Topic Modeling
Six major themes emerged:
- Wildfire and Flood Events
- Climate and Heat Coverage
- Hurricane Disaster Response
- Storm and Hurricane Tracking
- Community Impact and Damage
- Political Coverage

### Sentiment Analysis
- Fox News and NewsNation had the highest proportion of positive articles.
- NBC News and Sky News Australia showed relatively more negative framing.
- Fox News exhibited a negative correlation between climate attribution and sentiment (r = -0.554).

## Tools
- R
- tidyverse
- tidytext
- topicmodels
- sentimentr

## Skills Demonstrated
- Natural Language Processing (NLP)
- Text Mining
- Topic Modeling
- Sentiment Analysis
- Statistical Analysis
- Data Visualization
- Research Design

## My Contribution
As a member of the research team, I contributed to the core analytical components of the project, including:
- Co-designed the research framework and formulated the primary research questions regarding climate-change framing in extreme weather news coverage.
- Built the text preprocessing pipeline, including tokenization, stopword removal, lemmatization, and transcript cleaning.
- Conducted NLP analyses using TF-IDF, climate attribution scoring, topic modeling (LDA), and sentiment analysis.
- Interpreted analytical results and contributed to identifying climate attribution patterns across news organizations.

## Team Project
Team Members:
- Astrid Shao
- Jiayao(Claire) Liu
- Jingyi Chen
- Roselyn Yang

Repository maintained by Claire Liu.
