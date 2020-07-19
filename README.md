# amazon-product-recommendation-system

### In this project, I have created  a amazon product recommendation system which will recommend product on the basis of product similarity. 

## Major Steps followed during the project:

## 1.Data Gathering: 

Dataset has been downloaded from kaggle.The dataset consist of 7824482 rows and 4 columns. Since,the dataset is very large,subset of the dataset is taken (50000,4).

## 2.Feature Engineering: 

In this, first of all I have checked for the missing values in the dataset if any. In this, dataset there are no missing values.
Also, done exploratory data analysis to analyze the data with the help of seaborn library which is used for data visualization.

## 3.Model Training: 

After, all the data processing steps, I have created a pivot table which tells which person has purchase which product and how much rating has been given to that particular product. Before, fitting the dataset into model the matrix which is generated from pivot table is converted into sparse matrix using the CSR representation by calling the csr_matrix() function.
Now, I have used Nearest Neighbour is used which is an unsupervised machine learning algorithm which find the k most similar items to a particular instance based on the distance metric like euclidean distance.
