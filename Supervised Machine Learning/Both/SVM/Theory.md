# SUPPORT VECTOR MACHINE
![](https://tse4.mm.bing.net/th?id=OIP.SGumIn8hES6OhQdFXZ_uxAHaCc&pid=Api&P=0)<br/>
<br/>
The areas where SVM is currently in use 
1. Face detection
2. Classification of images
3. Text and hypertext categorization
4. Bioinformatics
5. Geo and Environmental Science
6. Handwriting recognition<br/>
<br/>
why Support Vector Machine ?<br/>
<br/>
SVM is a model that can predict unknown data. For example, if we have a pre-labeled data of pineapple and dragon fruit, we can easily train our model to identify pineapple and dragon fruit. So, whenever we give it new data – an unknown one – it can classify it under pineapple or dragon fruit. <br/>
<br/>
Types of SVM

1. Linear SVM
2. Non-linear SVM

**Linear SVM**: Linear SVM is used for linearly separable data, which means if a dataset can be classified into two classes by using a single straight line, then such data
is termed as linearly separable data, and classifier is used called as Linear SVM classifier.

**Non-linear SVM**: Non-Linear SVM is used for non-linearly separated data, which means if a dataset cannot be classified by using a straight line, then such data is termed as non-linear data and classifier used is called as Non-linear SVM classifier.

![](https://tse2.mm.bing.net/th?id=OIP.Fjj7EblDs2J88GgJmyKL8wHaE8&pid=Api&P=0)<br/>
<br/>
**Hyperplane**: There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points. This best boundary is known as the hyperplane of SVM.<br/>
We always create a hyperplane that has a maximum margin, which means the maximum distance between the data points.

**Support Vectors**
The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.<br/>
<br/>
**But how does the prediction take place?**

Here, we have our Support Vector Machine where we take the labeled sample of data as seen in the first graph. 
Further, we draw a line separating the two categories. This line is called the decision boundary. Herein one side of the decision boundary has apples and the other side has strawberries.
Now when new data is taken as seen in the third graph, it automatically goes into the group it belongs to – the right or the left side of the decision boundary.
And depending on which side of the line the unknown sample data goes, we can predict the unknown and classify it under the apple or strawberry category.<br/>
<br/>
So, now you know exactly what support vectors are. They are the extreme points in data sets. And these extreme points are separated by the maximum distance via the hyperplane. The unknown data sets falling on the left or right side of the hyperplane are classified into their respective categories.<br/>
<br/>
Let’s look at a more complicated example

The previous example was a simple one because the data sets were nicely segregated in the first place. But what if we have a data set that looks like this<br/>
<br/>
![](https://tse4.mm.bing.net/th?id=OIP.vxmJ2D5uAEuI0qFh3SiEUAHaFj&pid=Api&P=0)<br/>
<br/>
**There is no clear segregation. Well, in that case, how do we draw a hyperplane?**
Through kernel function. Kernel function takes the 1-d input and converts it into 2-d output.<br/>
<br/>
![](https://tse4.mm.bing.net/th?id=OIP.21hivvEpwz5Eum3mNwsFjwHaDG&pid=Api&P=0)<br/>
<br/>
### Advantages of Support Vector Machine (SVM)
1. **Regularization capabilities**: SVM possesses the L2 Regularization (Ridge regression) feature. L2 Regularization adds the squared magnitude of coefficient as penalty term to the loss function. It can generalize well which prevents it from over-fitting (modeling error which occurs when a function is closely fit in a limited set of data points).

2. **Handles non-linear data efficiently**: SVM efficiently handles non-linear data (where data items are not organized sequentially) through Kernel function.

3. **Solves both Classification and Regression problems**: SVM is used for classification problems while SVR (Support Vector Regression) is used for regression problems.

4. **Stability**: If there’s a slight change in the data, it does not affect the hyperplane, thereby confirming the stability of the SVM model.<br/>
<br/>

### Disadvantages of Support Vector Machine (SVM)

1. **Choosing an appropriate Kernel function is difficult**: Choosing an appropriate Kernel function (to handle the non-linear data) involves complexity. What happens is –  when you use a high dimensional kernel function, you might end up generating too many support vectors and that reduces the training speed. 

2. **Extensive memory requirement**: You obviously need a lot of memory to store all the support vectors in the memory. This number keeps on growing with the training dataset size.

3. **Long training time**: SVM requires a long training time on large datasets.

### Links to refer
1. [The Mathematics Behind Support Vector Machine Algorithm](https://www.analyticsvidhya.com/blog/2020/10/the-mathematics-behind-svm/)
2. [Support Vector Machine — Introduction to Machine Learning Algorithms](https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47)
3. [Support Vector Machines for Machine Learning](https://machinelearningmastery.com/support-vector-machines-for-machine-learning/)
4. [Support Vector Machine & PCA Tutorial for Beginner Kaggle](https://www.kaggle.com/code/faressayah/support-vector-machine-pca-tutorial-for-beginner?scriptVersionId=55513076)
5. [SVM Classifier Tutorial Kaggle](https://www.kaggle.com/code/prashant111/svm-classifier-tutorial)
6. [Support Vector Machines (SVM) Explanation & Mini-Project](https://medium.com/@youness.habach/support-vector-machines-svm-explanation-mini-project-9d4b4962be52)
7. [How to use the Support Vector Machine (SVM) as a classifier](https://medium.com/mlearning-ai/how-to-use-the-support-vector-machine-svm-as-a-classifier-e3b597d1b125)


















