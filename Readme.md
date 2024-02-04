 

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
    
- [x] [Tutorial 4: Bayesian Neural Network](Tutorial4/main.ipynb)

<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial4/main.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

 The topics covered in `Tutorial4/main.ipynb`  are: 

    - Bayesian Neural Network *Lecture 10.*
    - Buiding the BNN from Pytorch model
    - Bayes-by-backprop algorithm for training BNN. 
    - Compare the BNN with NN using the same neural network architecture and learning setting.
    - Also, how to train a simple network for regression task. 

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