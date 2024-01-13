## Tutorial 3: Feature Selection and P-value Calculation

by *Suwichaya Suwanwimolkul, Ph.D.*

Support `Lecture III: Linear Regression` ...


Let's start 

1. Feature Selection 

Here, we follow the content of variable selections from [Prof. Songsiri EE575 Chapter II Linear Regression](http://jitkomut.eng.chula.ac.th/ee575/linreg.pdf)
 

<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial3/FeatureSelection.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

or you can run `FeatureSelection.ipynb` locally for the coding exercies and examples used as parts of `Lecture III: Linear Regression` 
 
The topics covered in this exercise are: 

- [Get to know the Vehicle dataset](#data-visualization--preprocessing)
- [Linear model with all 8 features](#linear-regression-model-using-all-8-features)
    - [Training the model and inference](#perform-training-and-inference)
    - [Evaluation of the model](#model-evaluations)
- [Feature selection](#feature-selection)
    - [Correlation Matrix](#correlation-matrix-of-predictors-and-response)
- [Implementing some variable selection methods](#implementing-some-variable-selection-methods)
    - [Best subset selection](#best-subset-selection)
        - [Evaluation on the best subset](#test-with-the-selected-features-with-best-subset)
    - [Shinkage Method](#shrinkage-method)
        - [Lasso/Regression](#ridgelasso-regression)
        - [Evaluation on the set chosen by shinkage method](#test-with-the-selected-features-with-shrinkage-methods)
- [Performace Summary](#summary-of-all-three-methods) 

    

2. P-value ...


<a target="_blank" href="https://colab.research.google.com/github/GabbySuwichaya/Statistical-Learning-EE575/blob/master/Tutorial3/Pvalue.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>      

or you can run `Pvalue.ipynb` locally  ...

The topics covered in `Pvalue.ipynb`  are: 

- [Data visualization](#data-visualization--preprocessing)
- [Hypothesis Testing](#hypothesis-testing) 
    - [Statsmodels P-value](#by-statsmodels-package)
    - [P-value calculation](#implemention-of-the-hypothesis-testing)
        - [Steps of calculating P-value](#summary-of-the-steps) 


### Quick start 

You can try it locally by 

```
pip install numpy pandas tqdm matplotlib statsmodels ISLP
```

Then, start the jupyternote book [`main.ipynb`](main.ipynb).
 
 