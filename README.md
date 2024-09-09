# Statistical-Analysis-of-Narrative-Impact-on-Book-Popularity

# Overview
This analysis investigates the factors influencing the popularity of English-language fiction books, with popularity measured by the number of downloads. The study focuses on how the Kullback-Leibler Divergence (KLD) values, which quantify the information revelation patterns within narratives, relate to the popularity of these books. Several narrative attributes, including pacing, sentiment, and genre, are also considered.

# Key Components
## 1. Narrative Structure Analysis
**KLD Metrics**: The analysis captures asymmetry (skewness), peakedness (kurtosis), cumulative effects (cumulative sum), and local trends (rolling mean) in narrative structure using KLD values.
**Book Attributes**: In addition to KLD values, attributes such as narrative pacing (speed), average sentiment score, and sentiment volatility are analyzed.

## 2. Methodology
**Data Processing**: Derives book-level measures from KLD values and other narrative attributes.
**Ordinary Least Squares (OLS) Regression**: Used to relate narrative measures and attributes to log-transformed download counts.
**LASSO Regression**: Identifies the most significant predictors impacting book downloads.

## 3. Key Findings
**Skewness in KLD** negatively impacts popularity, indicating uneven information revelation makes books less engaging.
**Rolling Mean of KLD** positively affects downloads, showing that consistent information revelation is favored.
**Cumulative KLD** negatively correlates with popularity, suggesting that significant deviations from expected narrative structures reduce reader engagement.
**Pacing (speed)**, **sentiment average**, and **sentiment volatility** are significant predictors, influencing reader interest and engagement.
## 4. Significant Predictors
The most critical factors identified by LASSO regression are:
Skewness KLD
Rolling Mean KLD
Pacing (speed)
Sentiment Average
Sentiment Volatility

# Conclusion
This analysis offers insights into how narrative characteristics and emotional tone influence the popularity of fiction books. Authors and publishers can apply these findings to optimize their narratives and improve reader engagement by focusing on consistency in information revelation, pacing, and emotional tone.
