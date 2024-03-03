## Tutorial 5: Support vector machine

by *Suwichaya Suwanwimolkul, Ph.D.*

Support `Lecture 15: Support vector machine` ...

<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial5/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this tutorial, we will build SVM for multi-class classification. 

  - SVM does not support multiclass classification natively. 
  - Two commonly used approaches that extend SVM for multiclass classification are 
  
    - One-vs-One and 
    - One-vs-Rest. 

  - In this exercise, we would like you to apply multiclass classification using SVM to classify number 0-10 from MNIST dataset. 
 
Specifically, we would like you to explore the following:  


- [1. Histogram plots](#1-histogram-plots)  to ensure that you have chosen the samples evenly from each class. 
    - You may randomly select 6000 samples for training and 1000 sample for testing.  
    - Then, show the distribution of labels in the selected training and testing samples.

- [2. Training and model selection](#2-training-and-model-selection)

    Let's assume that we choose the RBF kernel for SVM. 

    - You may separate your training set for tuning and validation. 
    - Show the following results:
        - The accuracy (or loss ) curves across of the validation set across different kernels and model parameters. 
        - Pick the best set of parameters and verify the final performance on the testing dataset.  

- [3. One-vs-One and One-vs-Rest](#3-one-vs-one-vs-one-vs-the-rest)

    To see the differences between One-vs-one and One-vs-the rest. Let’s observe the positive and negative supports.  
    
    - 3.a. one-vs-one classification
        - What is the number of supports and how is it related to the number of classes? 
        - Observe the positive and negative supports of the first separation, the last separation, and any where in the middle.
    - 3.b. one-vs-rest classification 
        - same question for the supports and number of classes. 
        - Also, observe the positive and negative supports of the first separation,  the last separation, and any where inbetween.
    

- [4. Visualization](#4-visualize-the-supports-positive-and-negative-supports)

    Can you tell the differences between the observation in (3.a) and (3.b)? 
    
    - For each observation, you may plot the mean shapes of the positive and negative supports & the histogram of the labels associated with the positive and negative supports.

    - [Mean shapes of the negative supports](#plot-the-mean-shapes-of-the-negative-supports)

    - [Histogram of labels associated with possitive and negative supports](#calculate-the-histogram-of-the-labels-associated-with-the-positive-and-negative-supports)