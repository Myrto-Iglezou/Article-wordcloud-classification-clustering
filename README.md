# Article-wordcloud-classification-clustering

data: a directory of articles, which are classified in five categories (business, entertainment, politics, sport, tech)

Query 1| Create WordCloud

Create a WordCloud of each category, using the text of all the articles in this category.

Query 2| Classification

Use the classifiers:
* SVM
* Random Forests
* Naive Bayes and 
* K-Nearest Neighbor ( create the algorithm your self). 

Evaluate your classifier using:
* Precision/ Recall/ F-Measure
* Accuracy
* ROC plot

Query 3| Beat the Benchmark

Finally you should experiment with any Classification method you want, doing any pre-processing of the data you wish, in order to exceed as much as you can your performance in the previous query.

Query 4| Clustering 

In this query you need to implement clustering in the various text files.
The number of clusters for each query will be 5. The clustering will be done using the K-Means clustering algorithm. The distance function to be used is Cosine Similarity. K-Means will be applied to the data training set. Clustering should be implemented without using the Category variable. The clustering should be done in the following different representations of the texts:
● In the corresponding document-words table that will result from the BoW representation of the texts (both in simple counts, and separately in the tf-idf transformation of the counts)
● In the corresponding document-embeddings table that will appear using pre-trained embeddings (one of word2vec, glove, fast-text).

Also, visualize the distribution of texts in the space and make visible the group (cluster) they belong to, as well as their actual class. To be able to view points in 2 dimensions, use a compression method from Principal Component Analysis (PCA), Singular Value Decomposition (SVD) or Independent Component Analysis (ICA) (if you use all 3 you get a bonus). You will apply the compression method to both of the previously mentioned representations.
