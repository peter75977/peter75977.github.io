---
layout: page
title: labs & assignments
description: Ben Harvey's assignments
---


<div class="navbar">
    <div class="navbar-inner">
        <ul class="nav">
            <li><a href="#Assignment0">Assignment0</a></li>
            <li><a href="#Assignment1">Assignment1</a></li>
            <li><a href="#Assignment2">Assignment2</a></li>
            <li><a href="#Assignment3">Assignment3</a></li>
            <li><a href="#Assignment4">Assignment4</a></li>
            <li><a href="#ExtraCredit">Extra Credit Assignment</a></li>
            <li><a href="#labassignments">Lab Assignments</a></li>
        </ul>
    </div>
</div>


### EMSE 6992 Assignments
####  <a name="Assignment0"></a>Assignment0
#### Opens N/A and Due N/A
##### <a name="introduction"></a>introduction to Python, Jupyter Notebooks, Github, and Portfolios
* [Lab: Installing and Editing Portfolios](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/Portfolio_Setup.ipynb)

        In this in class, we will be using a variety of tools that will require some initial configuration including Python, Jupyter Notebooks, Github, and your Portfolio. To ensure everything goes smoothly moving forward, we will setup the majority of those tools in this in class activity.

Assignment    |    Repository
---   |   ---
[assignment0](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/HW0.ipynb)   |      [assignment0 repositiory](https://github.com/bsharvey/EMSEDataAnalytics)

---


####  <a name="Assignment1"></a>Assignment1
#### Opens 9/10 and Due 10/1
##### <a name="datamanipulationandaggregation"></a>data maniuplation and aggregation
* [Lab: Exploratory Data Analysis for Classification using Pandas and Matplotlib](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_eda/lab3.ipynb)

        In Part 1 of the assignment, the goals of this assignment are:
            To practice data manipulation with Pandas
            To develop intuition about the interplay of precision, accuracy, and bias when making predictions
            To better understand how election forecasts are constructed

##### <a name="visualization"></a>visualization
* [Lab: Exploratory Data Analysis for Classification using Pandas and Matplotlib](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_eda/lab3.ipynb)

Applying different visualization techniques to Part 1

Assignment    |    Repository
---    |    ---
[assignment1](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/HW1.ipynb)    |       [assignment1 repositiory](https://github.com/bsharvey/EMSEDataAnalytics/tree/master/EMSE6992_Assignments)

---


####  <a name="Assignment2"></a>Assignment2
#### Opens 10/1 and Due 10/22
##### <a name="scientificcomputing"></a>scientific computing
* [Lab: Scikit-Learn, Regression, PCA](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_scikitlearn_regression_pca/Lab4.ipynb)

        The goal of this assignment is to introduce Scikit-Learn and its functions, Regression, and PCA, and still more regression.  All objects within scikit-learn share a uniform common basic API consisting of three complementary interfaces: an estimator interface for building and ﬁtting models, a predictor interface for making predictions and a transformer interface for converting data.  The estimator interface is at the core of the library. It deﬁnes instantiation mechanisms of objects and exposes a fit method for learning a model from training data. All supervised and unsupervised learning algorithms (e.g., for classiﬁcation, regression or clustering) are oﬀered as objects implementing this interface. Machine learning tasks like feature extraction, feature selection or dimensionality reduction are also provided as estimators.



##### <a name="statisticalanalysis"></a>statistic alanalysis
* [Lab: Bias, Variance, Cross-Validation](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_bias_variance_crossvalidation/Lab5.ipynb)
* [Lab: Bayes, Linear Regression, and Metropolis Sampling](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_bayes_linearregression_sampling/BayesLinear.ipynb)

        In this lab, and in homework 2, we alluded to cross-validation with a weak explanation about finding the right hyper-parameters, some of which were regularization parameters. We will have more to say about regularization soon, but lets tackle the reasons we do cross-validation. The bottom line is: finding the model which has an appropriate mix of bias and variance. We usually want to sit at the point of the tradeoff between the two: be simple but no simpler than necessary.  We do not want a model with too much variance: it would not generalize well.  This phenomenon is also called overfitting. There is no point doing prediction if we cant generalize well. At the same time, if we have too much bias in our model, we will systematically underpredict or overpredict values and miss most predictions. This is also known as underfitting.  Cross-Validation provides us a way to find the "hyperparameters" of our model, such that we achieve the balance point.

Finally, this lab will address the Bayesian formulation of regression and the posterior predictive distribution and Markov/Metropolis-Hastings/Monte-Carlo sampling

| Assignment                | Repository                 |
| ------------------------- |:--------------------------:|
| [assignment2           ](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/HW2.ipynb)| [assignment2 repositiory](https://github.com/bsharvey/EMSEDataAnalytics)|

---


####  <a name="Assignment3"></a>Assignment3
#### Opens 10/22 and Due 11/12
##### <a name="deeplearning"></a>machine learning part1
* [Lab: Neural Networks](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_neuralnetworks_svm/Lab_10.ipynb)

Classification

    Identifying to which category an object belongs to.
    Applications: Spam detection, Image recognition.
    Algorithms: SVM, nearest neighbors, random forest, …

Regression

    Predicting a continuous-valued attribute associated with an object.
    Applications: Drug response, Stock prices.
    Algorithms: SVR, ridge regression, Lasso, …

Clustering

    Automatic grouping of similar objects into sets.
    Applications: Customer segmentation, Grouping experiment outcomes
    Algorithms:  k-Means, spectral clustering, mean-shift, …


##### <a name="machinelearning"></a>machine learning part2
* [Lab: Support Vector Machines](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_neuralnetworks_svm/Lab_10.ipynb)


Dimensionality reduction

    Reducing the number of random variables to consider.
    Applications: Visualization, Increased efficiency
    Algorithms: PCA, feature selection, non-negative matrix factorizations

Model selection

    Comparing, validating and choosing parameters and models.
    Goal: Improved accuracy via parameter tuning
    Modules:  grid search, cross validation, metrics.

Preprocessing

    Feature extraction and normalization.
    Application: Transforming input data such as text for use with machine learning algorithms.
    Modules: preprocessing, feature extraction.

| Assignment                | Repository                 |
| ------------------------- |:--------------------------:|
| [assignment3           ](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/HW3.ipynb)| [assignment3 repositiory](https://github.com/bsharvey/EMSEDataAnalytics)|

---



####  <a name="Assignment4"></a>Assignment4
#### Opens 11/12 and Due 12/3
##### <a name="portfolioimplementation"></a>portfolio implementation
* [Tutorial: Portfolio Template Modifications](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/Portfolio_Setup.ipynb)

        The goal of this assignment is for each student to have all tabs/links within the portfolio properly updated with their pertinent information (Resume, CV, bio, contact info, etc.).  The student must also have incorporated links to all assignments in their portfolio, as well as updating the Resources and Toolkit sections with examples using the data and Python libraries.  

##### <a name="networkanalysis"></a>network analysis
* [Lab: Networks](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_networks_graphs/lab_9.ipynb)

        {Add description of example an assignment here}


##### <a name="bigdataanalytics"></a>big data analytics
* [Lab: MapReduce](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_mapreduce/lab8_mapreduce.ipynb)

        {Add description of example an assignment here}


| Assignment                | Repository                 |
| ------------------------- |:--------------------------:|
| [assignment4           ](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/Portfolio_Setup.ipynb)| [assignment4 repositiory](https://github.com/bsharvey/EMSEDataAnalytics)|

---


####  <a name="ExtraCredit"></a>Extra Credit Assignment
##### <a name="webscraping"></a>webs craping
* [Lab: Web Scraping - Part 1](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_webscraping/Lab_2_A_Live.ipynb)
* [Lab: Web Scraping - Part 2](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_webscraping/Lab_2_B_Live.ipynb)


        {Add description of example an assignment here}


##### <a name="textprocessing"></a>sampling and text processing
* [Lab: Sampling and Text Processing ](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_sampling_textprocessing/GibbsSampler.ipynb)

        {Add description of example an assignment here}


| Assignment                 | Repository                 |
| -------------------------- |:--------------------------:|
| [Extra Credit           ]()| [Extra Credit repositiory](https://github.com/bsharvey/EMSEDataAnalytics)|

---


#### EMSE 6992 Labs
##### <a name="labassignments"></a>lab assignments

* [Week 1: Installing and Editing Portfolios - Part 1](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/Portfolio_Setup.ipynb)
* [Week 2: Installing and Editing Portfolios - Part 2](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Assignments/Portfolio_Setup.ipynb)
* [Week 3: Exploratory Data Analysis for Classification using Pandas and Matplotlib - Part 1](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_eda/lab3.ipynb)
* [Week 4: Web Scraping](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_webscraping/Lab_2_A_Live.ipynb)
* [Week 5: Exploratory Data Analysis for Classification using Pandas and Matplotlib - Part 2](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_eda/lab3.ipynb)
* [Week 6: MapReduce](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_mapreduce/lab8_mapreduce.ipynb)
* [Week 7: Scikit-Learn, Regression, PCA](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_scikitlearn_regression_pca/Lab4.ipynb)
* [Week 8: Bayes, Linear Regression, and Metropolis Sampling](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_bayes_linearregression_sampling/BayesLinear.ipynb)
* [Week 9: Sampling and Text Processing ](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_sampling_textprocessing/GibbsSampler.ipynb)
* [Week 10: Support Vector Machines and Neural Networks](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_neuralnetworks_svm/Lab_10.ipynb)
* [Week 11: Bias, Variance, Cross-Validation - Part 1](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_bias_variance_crossvalidation/Lab5.ipynb)
* [Week 12: Bias, Variance, Cross-Validation - Part 2](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_bias_variance_crossvalidation/Lab5.ipynb)
* [Week 13: Holiday]()
* [Week 14: Networks](https://github.com/bsharvey/EMSEDataAnalytics/blob/master/EMSE6992_Labs/lab_networks_graphs/lab_9.ipynb)
* [Week 15: Presentations]()

---
