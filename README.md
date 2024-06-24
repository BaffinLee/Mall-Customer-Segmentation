# Mall-Customer-Segmentation

You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

In this project I will use unsupervised learning method like K-means and NMF (Non-negative Matrix Factorization) ro clustering customers and find out my target customers.

## Code and Report

Please view code and description in [Jupyter notebook](https://github.com/BaffinLee/Mall-Customer-Segmentation/blob/main/Mall-Customer-Segmentation.ipynb).

## Conclusion and Discussion

In this project we used two unsupervised learning method to group our store's target customers.

By domain knowledge we know that customer with higher incom and spending score is our target customer.

So in the process of model training and testing, we care annual income and spending score cloumn most.

With the cluster plot we generated from each model, the K-means cluster plot is more intuitive. The group we got from K-means model is more well-cluster, the edge between each cluster is more clear. So we think K-means model is better for this project.

After we got the target customers list, we can apply marketing strategy to them. I am sure the target customers list will help increase our stores revenue.
