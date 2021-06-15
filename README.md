# Jairo_Portfolio
Welcome to my portfolio!! I have special interest in machine learning and deep learning technics, and Internet of Things

# [Fetch_lfw_people dataset: Facial Recognition with Support Vector Machines](https://github.com/jairo-deep-learning/fetch_lfw_people_svm/blob/main/Face_recognition_svm.ipynb)
This dataset is a collection of JPEG pictures of famous people collected over the internet, all details are available on the official website:

http://vis-www.cs.umass.edu/lfw/

The purpose in this project is to recognize the face of person in the picture and label it with its full name, based on a training process composed by thousand of labeled pictures.

For this project, all picture are black & white (sklearn.datasets.fetch_lfw_people -- parameter color = False)

Finally, for this project each class in dataset has at least 60 values.

![](/images/svc_predictions.png)

# [Boston dataset: Price estimation using Regression Decision Trees and Regression Random Forest](https://github.com/jairo-deep-learning/boston_regression_decision_tree/blob/main/Regression_decision_tree.ipynb)
This project used Boston dataset to estimate price of houses. For this case, supervised learning technics as Regression Decision Tree and Regression Random Forest were used to evaluate data.

![](/images/reg_decision_tree.png)

# [Iris dataset: Species detection using Decision Trees and Randon Forest](https://github.com/jairo-deep-learning/iris_decision_tree/blob/main/Decision_Trees.ipynb)
Species detection using Decision Trees and Random Forest technics. Iris is a very popular dataset used for accelerating learning curve in data scientists. Other machine learning technics can be run for Iris dataset, like Logistic Regression and KNN.

![](/images/iris_decision_tree.png)

# [Cancer dataset: Breast cancer detection using knn](https://github.com/jairo-deep-learning/breast_cancer/blob/main/KNN.ipynb)
K-NN is a machine learning technic used to classify data analysing similarity in features of data. In this project, K parameter was tested in several values: 3, 5, 7, 9 and 12. At the end, best performance was reached when K = 5, with a precision rate > 98%.

![](/images/knn-scatter.png)

# [Wine dataset: Unsupervised learning for clustering wine references](https://github.com/jairo-deep-learning/wine/blob/main/Wine_segmentation.ipynb)
It is well known that wine has motivated people to socialize, create, party, and adventure. It’s no wonder, billions of people around the globe identify as wine lovers!

In this dataset, we find 1600 wine references with the following features:

* Fixed acidity
* Volatile acidity
* Citric acid
* Residual sugar
* Chlorides
* Free sulfur dioxide
* Total sulfur dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality

The goal of this project is to create clusters that group references by similarity. This way, we could classify a new wine reference, that has not been included in this analysis, in one of the clusters defined here.

![](/images/dendrogram.png)

# [Advertising dataset: How to predict sales based on advertising investements](https://github.com/jairo-deep-learning/advertising/blob/main/Linear_regression_using_Scikit_learn.ipynb)
Marketing teams usually promote their products in different kind of media. For example: TV, radio, newspaper, social media, etc. 
However, the impact in sales could be different for each kind of media. Perharps, investing in TV or radio would generate
a bigger sales growth than investing in newspaper!! 
In this repository, you will find a model to predict sales based on different kind of media and also, it will help to
identify which kind of advertising should be performed by the company. 

![](/images/scatter_linear_regression.png)

# [Bank dataset: Predicting clients for financial services](https://github.com/jairo-deep-learning/Bank/blob/main/Logistic_regression%20(1).ipynb)
Many companies directs marketing campaings to all their leads. However, the effect of this campaings could be different from one potencial customer to other. So, what if marketing teams could have the possibility to predict which customer will buy from the mass of clients???

Well, in this analysis we try to create a model that allow us to predict who is going to buy a bank service and who is not. 

![](/images/ROCcurve.png)
