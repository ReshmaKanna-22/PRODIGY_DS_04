# Sentiment Analysis on Twitter Data #

### Introduction: ###
This analysis aims to explore sentiment patterns in the Twitter dataset from Kaggle. The dataset contains two Excel files: train and validation, which include tweets and their associated sentiment labels (positive, neutral, negative).

### Methodology ###
**1. Data Loading:**
- Pandas, matplotlib, seaborn, and WordCloud libraries are imported.
- The training and validation datasets are loaded from the specified file paths.

**2. Preprocessing the Data:**
- The train and validation datasets are combined for unified analysis.
- Missing values are identified and dropped.

**3. Basic Sentiment Distribution:**
- The distribution of sentiment labels is plotted to understand the overall sentiment composition in the dataset.

**4. Word Cloud for Each Sentiment:**
- Word clouds are generated for positive, neutral, negative and irrelevant sentiments to visualize the most frequent words in each category.

**5. Sentiment Analysis by Length of Tweet:**
- The length of each tweet is calculated.
- The distribution of tweet lengths across different sentiments is analyzed using a box plot.

**6. Sentiment Analysis by Tweet Entity:**
- Sentiment distribution by the entities is analyzed.

### Results: ###
- The sentiment distribution plot reveals the proportions of positive, neutral, negative and irrelevant sentiments.
- Word clouds highlight common words used in tweets of each sentiment category.
- Analysis of tweet lengths shows how tweet length varies with sentiment.
- Sentiment distributions by the entity provide insights into whether certain entities (e.g., brands, people) receive predominantly positive or negative sentiments.
