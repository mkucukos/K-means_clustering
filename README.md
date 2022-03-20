# K-means_clustering

I try to cluster the data based on the features such as age, gender, annual income, and spending score. Customer behavior and purchase data are among the aspects that influence a consumer's spending Score. I used the elbow method to choose the number of clusters by fitting the model with a range of values for K. From K=5, the WCSS (the sum of squared distances between each point and the cluster's centroid) begins to move practically parallel to the X-axis. The model output for 5 clusters was visualized in 2D as a function of annual income and spending score.

```bash
$ pip install -r requirement.txt
```
![model's output](./figure1.png)
![model's output](./figure2.png)

