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

<h3>Step 2</h3>
Before jumping into creating our classifier, let’s take a look at the data. Begin by printing breast_cancer_data.data[0]. That’s the first datapoint in our set. But what do all of those numbers represent? Let’s also print breast_cancer_data.feature_names.

<h3>Step 3</h3>
We now have a sense of what the data looks like, but what are we trying to classify? Let’s print both breast_cancer_data.target and breast_cancer_data.target_names.

<h4>Was the very first data point tagged as malignant or benign?</h4>
The very first data point was tagged as a 0 which is malignant.

<h2>Splitting Data into Training and Validation Sets</h2>

<h3>Step 4</h3>
We have our data, but now it needs to be split into training and validation sets. Luckily, sklearn has a function that does that for us. Begin by importing the train_test_split function from sklearn.model_selection.

<h3>Step 5</h3>
Call the train_test_split function. It takes several parameters:
<ul>
<li>The data you want to split</li>
<li>The labels associated with that data</li>
<li>The test_size</li>
<li>random_state</li>
</ul>

<h3>Step 6</h3>
Right now we’re not storing the return value of train_test_split. train_test_split returns four values in the following order:
<ul>
<li>The Training Set</li>
<li>The Validation Set</li>
<li>The Training Labels</li>
<li>The Validation Labels</li>
</ul>
Store those values in variables named training_data, validation_data, training_labels, and validation_labels.

<h3>Step 7</h3>
Let’s confirm that worked correctly. Print out the length of training_data and training_labels. They should be the same size - one label for every piece of data!
<h4>Both are 455 so this worked</h4>

<h2>Run the Classifier</h2>