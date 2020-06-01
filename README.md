# cs236756-intro-to-ml
Jupyter Notebook tutorials for the Technion's CS 236756 course "Introduction to Machine Learning"

<img src="https://github.com/taldatech/cs236756-intro-to-ml/blob/master/assets/tut_08_adaline.gif" width="300"> <img src="https://github.com/taldatech/cs236756-intro-to-ml/blob/master/assets/tut_06_gd.gif" width="300">

* For the old tutorials, see `spring19` branch.

- [cs236756-intro-to-ml](#cs236756-intro-to-ml)
  * [Running The Notebooks](#running-the-notebooks)
    + [Running Online](#running-online)
    + [Running Locally](#running-locally)
  * [Agenda](#agenda)
  * [Installation Instructions](#installation-instructions)
    + [Libraries to Install](#libraries-to-install)

## Running The Notebooks
You can view the tutorials online or download and run locally.

### Running Online

|Service      | Usage |
|-------------|---------|
|Jupyter Nbviewer| Render and view the notebooks (can not edit) |
|Binder| Render, view and edit the notebooks (limited time) |
|Google Colab| Render, view, edit and save the notebooks to Google Drive (limited time) |


Jupyter Nbviewer:

[![nbviewer](https://jupyter.org/assets/main-logo.svg)](https://nbviewer.jupyter.org/github/taldatech/cs236756-intro-to-ml/tree/master/)


Press on the "Open in Colab" button below to use Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/taldatech/cs236756-intro-to-ml)

Or press on the "launch binder" button below to launch in Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/taldatech/cs236756-intro-to-ml/master)

Note: creating the Binder instance takes about ~5-10 minutes, so be patient

### Running Locally
Press "Download ZIP" under the green button `Clone or download` or use `git` to clone the repository using the 
following command: `git clone https://github.com/taldatech/cs236756-intro-to-ml.git` (in cmd/PowerShell in Windows or in the Terminal in Linux/Mac)

Open the folder in Jupyter Notebook (it is recommended to use Anaconda). Installation instructions can be found at the bottom of the README file.



## Agenda

|File       | Topics Covered |
|----------------|---------|
|`cs236756_tutorial_01_probability_mle.ipynb\pdf`|  Probability basics, random variables, Bayes rule, histograms, correlation, parameter estimation, Maximum Likelihood Estimation (MLE)|
|`cs236756_tutorial_02_statistics.ipynb\pdf`|Statistics definitions, hypothesis testing steps, z-statistic, Central Limit Theorem (CLT), Area Under the Curve (AUC), error types, confusion matrix|
|`cs236756_tutorial_03_linear_algebra.ipynb\pdf`|Linear Algebra basics (vectors, inner/outer product spaces, norms, linear dependency, matrix operations, matrix rank, range and nullspace), least-squares solution, eigenvalues and eigenvectors, Singuar Value Decomposition (SVD)|
|`cs236756_tutorial_04_pca_feature_selection.ipynb\pdf`|Dimensionality Reduction, Outliers, PCA, SVD, Breast Cancer dataset, Feature Selection, Filter methods, Wrapper methods, RFE (scikit-learn)|
|`cs236756_tutorial_05_evaluation_validation.ipynb\pdf`|Classifier Evaluation and Validation, metrics, accuracy, precision, recall, FN/TP rate, Confusion Matrix, F1 score, K-Fold Cross-Validation, train-validation-test split, holdout method, stratification, ROC curve|
|`cs236756_tutorial_06_decision_trees.ipynb\pdf`|Decision Trees, The CART algorithm, Pruning, Regularization, Impurity Metrics, Entropy, Gini, Information Gain (IG), SplitInformation, Gain Ratio (GR), The Titanic Dataset, Tree Visualization with Scikit-Learn, Random Forest, Mutual Information (MI)|
|`cs236756_tutorial_07_optimization.ipynb\pdf`|Optimization in ML, Gradient Descent, Batch Gradient Descent, Mini-Batch (MB) Gradient Descent, Stochastic Gradient Descent (SGD), Convexity, Uni/Multi-modal problems, Lagrangian and Largrange Multipliers, Constrained Optimization|
|`cs236756_tutorial_08_linear_regression.ipynb\pdf`|Classification vs. Regression, NLL (Negative Log-Likelihood), MLE connection to MSE, Residual Analysis, Basis Functions Expansion, Feature Extraction, Linear and Polynomial Regression, Bias-Variance Tradeoff, Irreducible Error, Regularization (L1 + L2), Ridge and LASSO Regression|
|`cs236756_tutorial_09_linear_models.ipynb\pdf`|Discriminative vs Generative Models, Linear Models, Perceptron, Least Mean Square (LMS) - Adaptive Linear Neuron (ADALINE), MLE with Bernoulli, Logistic Regression, Softmax, Maximum A Posteriori (MAP), Quadratic Discriminant Analysis (QDA), Naive Bayes, Linear Discriminant Analysis (LDA), One-vs-All Classification|
|`cs236756_tutorial_10_expectation_maximization.ipynb\pdf`|Soft Clustering, Hard Clustering, K-Means, Incomplete/Complete Likelihood, Expectation Maximization (EM) Algorithm, Gaussian Mixture Model (GMM), Bernoulli Mixture Model (BMM), Dataset Generation with Scikit-Learn|

## Installation Instructions
1. Get Anaconda with Python 3, follow the instructions according to your OS (Windows/Mac/Linux) at: https://www.anaconda.com/distribution/
2. Create a new environment for the course (full guide at https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands):
In Windows open `Anaconda Prompt` from the start menu, in Mac/Linux open the terminal and run `conda create --name ml_course`
3. To activate the environment, open the terminal (or `Anaconda Prompt` in Windows) and run `conda activate ml_course`
4. Install the required libraries according to the table below (to search for a specific library and the corresponding command you can also look at https://anaconda.org/)

### Libraries to Install
|Library         | Command to Run |
|----------------|---------|
|`Jupyter Notebook`|  `conda install -c conda-forge notebook`|
|`numpy`|  `conda install -c conda-forge numpy`|
|`matplotlib`|  `conda install -c conda-forge matplotlib`|
|`pandas`|  `conda install -c conda-forge pandas`|
|`scipy`| `conda install -c anaconda scipy `|
|`scikit-learn`|  `conda install -c conda-forge scikit-learn`|

5. To open the notbooks, run `jupyter notebook` in the terminal (or `Anaconda Prompt` in Windows) while the `ml_course` environment is activated.
