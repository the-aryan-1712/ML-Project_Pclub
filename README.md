<H3>CSVFiles<H3>  
<Pre>train.csv- for training data initially using KNN
test.csv-for testing the model.                              
sample_submission_given- already provided us with the real outcome of the test data
sample_submission_output- predicted data by model
gradio_test.csv- 5 features file for testing the gradio model
gradio_train2.csv- train file with 5 features to train the model in gradio and makingGUIinterface
</Pre>
<H2>Project Overview</H2>
<H3>1. K-Nearest Neighbors (KNN) for House Price Estimation:</H3>
<pre>
Data Preparation:
Loaded the house price dataset and inspect its structure.
Identified features (attributes) and the target variable (house prices).
</pre>
<pre>Data Preprocessing:
Handled missing values and null values with mode and mean.
Encoded categorical variables and scale numerical features using one-hot encoding.
</pre>
<pre>Train-Test Split:
Splitted the dataset into training and testing sets.
</pre>

<pre>KNN Model Training:
Implemented and trained a KNN regression model using the training set.
Experimented with different values of k and choose the one that provides the best performance
(e.g., using cross-validation).
</pre>

<pre>Model Evaluation:
Evaluated the model's performance on the testing set using metrics like Root Mean Squared Error
(RMSE).
</pre>
<pre>Insight and Observation:
Analyzed the features that contribute the most to the house price predictions.
Identified any non-linear relationships or patterns that the KNN model captures.
</pre>
<H3>2. Clustering for Insight using K-Means:</H3>
<pre>
Choosed a relevant features for clustering (like this include location, size, amenities, etc.).

Normalization/Scaling:
Normalized or scaled the selected features.

Determining the Number of Clusters (k):
Experimented with different values of k to find an optimal number of clusters. 
Techniques like the elbow method or silhouette score can help.
I used the elbow method so as to find best value of k(clusters)

Apply K-Means Clustering:
Used the chosen k to apply k-means clustering on the dataset.

Cluster Analysis:
Analyzed the cluster and which feature is dominating the most.
Most common feature in a cluster was the saleprice of house. 
</pre>
<H3>3.Correlation between KNN and Clustering Results:</H3>
<pre>KNN results predict the house prices with a good accuracy.On the other hand K-means collectivise the houses 
in 3 clusters which share a common property, which seems to be the house price in most of the cases while in 
some cases other features collectively take house in other cluster irrespective of being similar prices.

</pre>
<pre>
Suggested Areas for future exploration or improvement:
By combining KNN for regression and k-means clustering, we can gain a comprehensive understanding of house price 
trends and the factors that contribute to houses being grouped together. This integrated approach helps
provide richer insights for decision-making in the real estate domain.

</pre>