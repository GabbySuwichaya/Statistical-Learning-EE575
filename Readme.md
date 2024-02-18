 

Our goal is to provide the code-based visualization and exercises to understand the mathematics behind each of lectures in **Statiscal Learning EE2102575** by *Suwichaya Suwanwimolkul*.

 
### Topics

The coding scripts & excercises are 

- [x] [Tutorial 1:  Linear Regression *to support Lecture III* ](Tutorial1/main.ipynb) 

<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial1/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

    - Examples of how to use the OLS package
    - Exercise **
  
- [x] [Tutorial 2: Robust Regression *to support Lecture IV*](Tutorial2/main.ipynb) 

<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial2/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

    - Least Square Regression 
    - Robust Regression Model 
    - Robust Regression Model with Huber Loss ** Exercise 
    - Weighted Least Square ** Exercise

- [x] Tutorial 3: Feature Selection and P-value Calculation*

[Tutorial 3: Feature Selection](Tutorial3/FeatureSelection.ipynb)
  
  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial3/FeatureSelection.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>

  The topics covered in `FeatureSelection.ipynb` are:  

    - Feature selection  
    - Best subset selection 
    - Shinkage Method: Lasso/Regression  

  [Tutorial 3: P-Value](Tutorial3/Pvalue.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial3/Pvalue.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a> 
    
  The topics covered in `Pvalue.ipynb`  are: 

    - Hypothesis Testing
    - Statsmodels P-value
    - Steps of calculating P-value

- [x] [Homework 1: Implementing IRLS](Homework1/main.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Homework1/main.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>

  The topics covered in `main.ipynb`  are: 

  - Data Visualization and Preprocessing
  - Ordinary Least Square  
  - Weighted Least Square << You implementation >>  
  - Iterative Reweighted Least Square   << You implementation >> 
  - Compare all the results 
    
- [x] [Tutorial 4: Static Neural Network and Bayesian Neural Network](Tutorial4/main.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial4/main.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>

  The topics covered in `Tutorial4/main.ipynb`  are: 

    - Bayesian Neural Network *Lecture 10.*
    - Buiding the BNN from Pytorch model
    - Bayes-by-backprop algorithm for training BNN. 
    - Compare the BNN with NN using the same neural network architecture and learning setting.
    - Also, how to train a simple network for regression task. 
    - Our implementation is based on [Nitarshan's Bayes-by-backprop](https://github.com/nitarshan/bayes-by-backprop) and 'Weight Uncertainty Neural Network' JMRL 2018. 

- [x] [Tutorial 4: Quick start on Pyro](Tutorial4/Pyro_quickstart.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial4/Pyro_quickstart.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>

  In this tutorial, we will build a BNN with Pyro ...
   
  - [Install package](#installing-package)
  - [Import data](#import-data) 
  - [Bayesian neural network (Pyro)](#bayesian-neural-network-Pyro)    
  - [Training BNN](#training-bnn) 
  - [Prediction BNN](#prediction)

  Our implementation is based on [Pyro Stochastic Variational Inference](https://pyro.ai/examples/bayesian_regression.html#Bayesian-Regression-with-Pyro%E2%80%99s-Stochastic-Variational-Inference-(SVI)) 

- [x] [Lab 2: Neural Network Quiz, Static NN Implementation, BNN Implementation](Lab2/main.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Lab2/main.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>

  In this lab session/homework assignment, you will be tasked to 
  - Answering some quizzes about DNN  
  - Implementing the DNN from Pytorch model
  - Implementing the BNN from Pytorch model


- [x] [Lab 3: Classification quiz, Logistic regression, kNN, LDA, QDA](Lab3/main.ipynb)

  <a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Lab3/main.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>

  In this lab session/homework assignment, you will be tasked to 
  - Answering some quizzes about feature correlation, logistic regression, kNN, LDA, and QDA  
  - Implementing the logistic regression, kNN, LDA, and QDA  
  - Making analysis of the results and evaluation such as confusion matrix, precision-recall, etc.

### Getting Started

1. Change the directory to the `Tutorial` folder.
2. Look for the  instructions (e.g. [Tutorial 1 Readme](TutorialX/Readme.md)) for installing dependencies. 
3. You may execute the `main` file in python or ipynb fileformat. 

* Course materials (such as HW and lecture notes) maybe provided in each `Tutorial` folder. 
* Each tutorial runs independently in its own environment. 

### Citation 

```
@book{CUEE523,
  author        = {Suwichaya Suwanwimolkul},
  title         = {{L}ecture {N}otes on {S}tatiscal {L}earning {EE}575},
  month         = {Semester II},
  year          = {2023},
  publisher     = {Chulalongkorn Univeristy},
  url           = "https://github.com/GabbySuwichaya/Statistical-Learning-EE575"
}
```