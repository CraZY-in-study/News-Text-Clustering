# News-Text-Clustering
## Problem Defined:
The problem is to perform clustering analysis on news text data. The goal is to categorize the news into different groups based on their content.

## Data Preparation:
A dataset of 1,500 Chinese news texts was prepared. The texts were preprocessed using 'jieba' for word segmentation and stop words removal. This preprocessing resulted in a total of 35,766 words.

## Data Process:
- The preprocessed news texts were vectorized using the Vector Space Model with TF-IDF weighting.
- The optimal number of clusters (K) was determined to be 4 using the Elbow Method and Silhouette Coefficient Method.

## Data Analysis:
- The news texts were then clustered into 4 categories using the K-means algorithm.
- By analyzing the high-frequency words in each cluster, the 4 news categories were identified as: Education, Sports, Medical, and Gaming.

## Conclusion:
The clustering analysis of the news text data was successful in categorizing the news into four distinct categories. This demonstrates the effectiveness of using text preprocessing, TF-IDF vectorization, and K-means clustering in news text analysis.
