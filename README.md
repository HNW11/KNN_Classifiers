# KNN_Classifiers
Code Academy Project for K Nearest Neighbors Classifier 

Breast Cancer Classifier
In this project, we will be using several Python libraries to make a K-Nearest Neighbor classifier that is trained to predict whether a patient has breast cancer.

<h2>Explore the Data</h2>

<h3>Step 1</h3>
<ul>
<li>Let’s begin by importing the breast cancer data from sklearn. We want to import the function load_breast_cancer from sklearn.datasets.</li>
<li>Once we’ve imported the dataset, let’s load the data into a variable called breast_cancer_data. Do this by setting breast_cancer_data equal to the function load_breast_cancer().</li>
</ul>
<br>
<h3>Step 2</h3>
Before jumping into creating our classifier, let’s take a look at the data. Begin by printing breast_cancer_data.data[0]. That’s the first datapoint in our set. But what do all of those numbers represent? Let’s also print breast_cancer_data.feature_names.
<br>
<h3>Step 3</h3>
We now have a sense of what the data looks like, but what are we trying to classify? Let’s print both breast_cancer_data.target and breast_cancer_data.target_names.
<br>
<h4>Was the very first data point tagged as malignant or benign?</h4>
The very first data point was tagged as a 0 which is malignant.

<h2>Splitting Data into Training and Validation Sets</h2>
