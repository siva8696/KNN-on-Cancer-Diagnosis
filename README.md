In the name itself suggests that KNN is a nearest neighbor-based algorithm. KNN means K – nearest neighbors and where K is a hyperparameter it will be useful for us to select how many neighbors you want.  The number of neighbors should be an integer value. It will do both classification and regression problem. 

How the algorithm will work?

![KNN](https://i.stack.imgur.com/J5r01.png)
 
As if you consider the above diagram, where it is a classification task and X1 and X2 are two features. In the above diagram as we can see the points are almost well separated. So, let’s consider the K value as 10 and the blue point is our query point. So, if we consider the 10 nearest-neighbors of it there are 7 points are belonging to Class 1 and 3 points are belonging to Class 0 and based on majority voting we can classify the new query point as Class 1. Here you may raise one question, i.e. How do you identify the 10 points? Here we have identified the 10 points based on distance between query point and data points. There are two distance method we usually used. They are: Euclidean distance and Manhattan distance. Don’t forgot that as we are using distance based approach so we need to do scaling of features using normalization.

KNN for regression: Please refer the below article.

https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/
