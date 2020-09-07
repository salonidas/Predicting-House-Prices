# Predict House Prices with Regression using Tensorflow2.0

For this project, I have worked on predicting house prices given the following features:

1. Year of sale of the house
2. The age of the house at the time of sale
3. Distance from city center
4. Number of stores in the locality
5. The latitude
6. The longitude

<hr>
<h3>Pre-requisites / Preparation : </h3>
<b>This project is made using Anaconda distribution of python.</b> <br> 
 There are some general library requirements for the project which are as follows :
<ul>
 <li>
  <code>Tensorflow 2.0</code>
 </li>
 <li>
  <code>Pandas</code>
 </li>
 <li>
  <code>Utils</code>
 </li>
 <li>
  <code>Matplotlib</code>
 </li>
 <li>
  <code>Scikit-learn</code>
 </li>
 </ul>

<b> Steps for preparation : </b>
1. To set up this project first create a new virtual environment in Anaconda for Tensorflow.
2. Install <code>tensorflow</code> and <code>keras</code> libraries in the new env.
3. Then install all the regular python libraries (<code>pandas</code>, <code>utils</code>, <code>matplotlib</code>, <code>scikit-learn</code>).
4. Then follow the steps given below.

<hr>

<h3>Approach : </h3>

Step 1 : Introduction
1. Import libraries and helper functions. <br>
(For tensorflow 1.0, use - <b>tf.logging</b> in place of <b>tf.compat.v1.logging</b>)

Step 2 : The Dataset
1. Import the dataset. <br>
2. Check for missing data.

Step 3 : Data Normalization
1. Data normalization. <br>
2. Convert label price values back to original format.

Step 4 : Training and Test Sets
1. Select features. <br>
2. Select labels. <br>
3. Convert from Pandas data structures to numpy arrays. <br>
4. Train and test split.

Step 5 : Create the Model
1. Create a sequential model with Keras.  <br>
2. Model architecture - hidden layers and hidden units.  <br>
3. Compile the model by specifying an optimizer and a loss function. <br>
4. Compute trainable parameters.

Step 6 : Model Training
1. Train the model to fit to training data. <br>
2. Plot training and validation loss.

Step 7 : Predictions
1. Plot and compare raw predictions. <br>
2. Plot and compare price predictions.
