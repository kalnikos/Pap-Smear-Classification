# Pap-Smear-Classification

The goal of this project is to develop a classification model that will be able to identify the cervical dysplasia in two main categories, normal and abnormal. The data set that I’mworking on has a target divided into 7 categories depending on how serious the dysplasia is. In order to divide these categories I will try to implement two unsupervised methods aiming to find:
1.	The number of the clusters. 

2.	How I would split up these clusters.

In addition,I will  implement some techniques to determine highly correlated features and a dimension reduction method in order to identify patterns and divide the target column into less categories. 

My data has 26 features and 500 rows. Although I have to deal with many features the number of the rows is not so big and this is something that I will try to increase in order to develop another model and compare the results.Firstly, I used some statistics techniques to examine the distribution of the features and scatterplots aiming to find which variables are having high correlation.

![cor](https://user-images.githubusercontent.com/66875726/97926634-21763300-1d6c-11eb-91ff-4ba6dbc76721.png

Yes I know is a little bit chaotic, many features but after I used the Univariate Feature Selection method and I have to manage 15 features. 

![Χωρίς τίτλο](https://user-images.githubusercontent.com/66875726/97927626-04426400-1d6e-11eb-93c0-4b0e1c55659e.png)

After these steps I implemented two Unsupervised techniques in order to determine the number of the classes that I could split the data. I started with a Hierarchical algorithm and below is the dendrogram of the algorithm.   

![dend](https://user-images.githubusercontent.com/66875726/97928272-5a63d700-1d6f-11eb-8c35-62264709abce.png)









