# BACKGROUND:
In this current era of information explosion, textual data has become an indispensable part of
our daily lives. It is generated in massive volumes every second, from social media posts,
customer reviews, movie reviews, feedback, complaints and more. Analyzing this vast amount
of textual data is crucial in understanding this data and making use of it in business.

## Problem Background

Online reviews significantly influence consumer purchasing decisions, particularly in the food industry. Fine Food focuses on the key industry areas of bakery, confectionery, dairy, meat & seafood, and natural products.

Analyzing sentiments in these reviews helps businesses understand customer satisfaction, improve product offerings, and enhance customer experience.

\
\
High Review Volume: The Amazon Fine Food reviews dataset contains a large number of reviews, providing a robust sample for analysis.

Diverse Opinions: Reviews cover a wide range of products, reflecting diverse consumer opinions and sentiments.

Business Impact: Fine foods are a critical category where customer feedback directly impacts product development and marketing strategies.

Relevance: Sentiment analysis in the food sector helps identify trends, preferences, and areas needing improvement, directly benefiting producers and consumers.


## About Dataset

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review.

1. Reviews from Oct 1999 - Oct 2012
2. 568,454 reviews
3. 256,059 users
4. 74,258 products
5. 260 users with > 50 reviews


##  Objective

To achieve the aim in this project, several objectives have been issued which are:
1. To conduct data and text preprocessing on Amazon Fine Food Review.
2. To perform model development on predicting and clustering customer segments.
3. To evaluate model performance on clustering algorithms in different clustering.
4. To conduct customer feedback analysis on consumer’s review toward Amazon Fine Food by identified clusters.


## Conclusion: Results, Finding and Recommendations

In a nutshell the 3 clusters formed by Mini Batch K-Means were found to be reasonably compact and well-separated. Next, BIRCH also identified 3 clusters, demonstrating high-quality clustering with dense and well-separated clusters. Last but not least, HDBSCAN identified 4 clusters with extra detected a significant number of outliers as another cluster.
In comparing the performance of the clustering algorithms, Mini Batch K-Means and BIRCH both identified a similar clustering structure with three main clusters and displayed high clustering quality, as evidenced by their high Calinski-Harabasz scores, low Davies-Bouldin scores and high Silhouette scores. These metrics indicate strong separation between clusters and tight within-cluster cohesion. Mini Batch K-Means distinguished itself with exceptional computational efficiency, completing the clustering in just 0.123643 seconds, making it the fastest among the three algorithms.In conclusion, Mini Batch K-Means emerged as the best model due to its balance of high clustering quality and superior computational efficiency.
