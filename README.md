# Customer_segmentation

<img width="695" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/215c3797-c151-46a1-91e5-90e7407d1e8c">

<img width="689" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/8a09979c-baa6-42f9-a7e3-8dc93a2087bc">

<img width="674" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/1a2a0775-99eb-405e-9c43-3109f12cb8c4">

<img width="719" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/0d83d7ad-1630-4bbf-a045-9fd48379840a">

No missing values in the whole dataset

<img width="703" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/be244003-2c1d-4074-becb-a322fabf54d8">

<img width="689" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/a29aa6b9-81b0-4c41-98e0-4a4771d32c57">

Checking the unique values in each column, we can drop the column which have are sort of duplicates.

<img width="771" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/c6ceb30b-0cd1-4d52-b2ae-5833c7c7bc93">

Z_cost and Z_revenue are duplicate columns, so we can remove them from analysis.

<img width="706" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/8d9cdc8b-bb1b-410d-b6a8-217898e8bd01">

Checking for outliers

<img width="700" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/01324735-979e-4922-a773-ecd1abc37cc1">

The arrow above the boxplot indicates the presence of outliers in the dataset.

<img width="383" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/79b1a8ba-e58c-4fd5-b163-780ce3614fa5">

Looking at the outliers with the Interquartile Ranges.

<img width="727" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/e7e4d531-4d6d-4578-a2f0-f55fbda16e5a">

Removing the outliers from the dataset for better data modeling.

<img width="700" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/5d37fb98-04ff-47e7-8685-b7d5f13a9b1a">

<img width="694" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/6cfd6b46-dc41-4244-ba48-e1512f996ed6">

New boxplot for removing the outliers

<img width="510" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/b447c1b9-1f4b-45f5-b545-a1fdf4bedd6a">

Making correlation matrix to check which data column is most closely related.

<img width="696" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/0c8191f2-356a-4496-aa7b-7cb5a44d3da8">

<img width="695" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/5ccfd6fd-ecef-418d-a415-74096a38b867">

Correlation matrix for the dataset

<img width="365" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/bef06321-df77-4d73-97ca-ac2471e12e2e">

<img width="722" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/60a154a4-38b7-4ab8-84c2-c42710a96cae">

Marital Status of the Customers

<img width="417" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/888c417c-9448-4675-9b5a-1c05f0176f1b">

Importing Kmeans Clustering and preparing the data for Clustering model

<img width="655" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/54cec9e4-1f8c-42cc-bacf-07866cab3909">

Principal Component Analysis (PCA) for reducing the dimension of the dataset (to avoid dimensionality curse lol)

<img width="693" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/bee8fea5-dcd9-4d19-a9b9-64cfe0a51956">

Now using the elbow method to determine the optimal number of clusters (k) for the K-Means Clustering

<img width="698" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/f2fb7665-b77a-455a-a0c0-cd597fb84fe7">

Output

<img width="410" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/c0cac6ff-56fd-485d-9417-724388d72905">

Silhouette score analysis to check the quality of clustering

<img width="704" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/08ee85a2-1b9f-4608-84ff-9b7f318103c9">

Output

<img width="489" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/125a96df-9290-4ce1-bb67-ed21cde11b2c">

Visualizing the clusters

<img width="711" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/0d6e82e1-7fdd-4595-9323-6b4b50e99869">

Clustered data visualization

<img width="542" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/9ec86d5a-6188-4286-bc66-58520dfdac4c">

Mean Consumption on diff product types by cluster

<img width="689" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/05b6c64f-9381-41a0-90e0-01a5668cc402">

<img width="686" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/b5c894fd-004e-4890-ad52-9501ac4423e6">

Visualizing the consumption of the various product

<img width="647" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/38cbd3c1-81ec-4cc2-b69d-21b99710e5e2">

Cluster sizes and visualization 

<img width="702" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/c7fe2586-9007-4bad-b4d4-76f5210d7fb1">

<img width="544" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/ca8f5df1-1bc6-40d7-8295-3bb99fa2a76f">

Boxplot of the income by cluster

<img width="680" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/aeffb3ec-2fdf-45aa-9d65-b896781f68f3">

<img width="559" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/2d4784dc-0da4-45ee-82ea-8fc1c4ea73ca">

Scatter Plot of the Income

<img width="683" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/345e16de-73f6-414e-830c-ca7714ff7eca">

<img width="515" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/08874718-d997-48bf-ab18-112d61c715ff">

Features of the Clusters

<img width="720" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/899aa0da-72bb-47de-8ed0-52feb11ff98c">

<img width="500" alt="image" src="https://github.com/pratt12/Customer_segmentation/assets/69366735/e17f481e-71ca-444b-9f35-b3e20a676487">

# Results

Optimal number of clusters = 4
The Elbow Method and Silhouette Analysis suggested 4 clusters (k=4). The elbow method highlighted the number of 4 or 5 clusters as a reasonable number of clusters. The silhouette score analysis revealed a peak silhouette score for k=4.

# Cluster Characteristics

Cluster 0: High value customers in relationship (either married or together)
This cluster represents 26% of the customer base. These customers have high income and they are in a relationship

Cluster 1: Low value single customers
This cluster represents 21% of the customer base. These customers have low income and they are single

Cluster 2: High value single customers
This cluster represents 15% of the customer base. These customers have high income and they are single

Cluster 3: Low value customers in relationship
This cluster represents 39% of the customer base. These customers have low income and they are in a relationship














































