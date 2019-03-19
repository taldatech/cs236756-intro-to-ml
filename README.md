# cs236756-intro-to-ml
Jupyter Notebook tutorials for the Technion's CS 236756 course "Introduction to Machine Learning"

## Running The Notebooks
You can the tutorials online or download and run locally.

### Running Online
Press on the "Binder" button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/taldatech/cs236756-intro-to-ml/master)

### Running Locally
Press "Download ZIP" under the green button `Clone or download` or use `git` to clone the repository using the 
following command: `git clone https://github.com/taldatech/cs236756-intro-to-ml.git` (in cmd/PowerShell in Windows or in the Terminal in Linux/Mac)

Open the folder in Jupyter Notebook (it is recommended to use Anaconda). Installation instructions can be found at the bottom of the README file.



## Agenda

|File       | Topics Covered |
|----------------|---------|
|`cs236756_tutorial_01_probability_mle.ipynb`|  Probability basics, random variables, Bayes rule, histograms, correlation, parameter estimation, Maximum Likelihood Estimation (MLE)|
|`cs236756_tutorial_02_statistics.ipynb`|  Statistics definitions, hypothesis testing steps, z-statistic, Central Limit Theorem (CLT), Area Under the Curve (AUC), error types, confusion matrix|
|`cs236756_tutorial_03_linear_algebra.ipynb`|  Linear Algebra basics (vectors, inner/outer product spaces, norms, linear dependency, matrix operations, matrix rank, range and nullspace), least-squares solution, eigenvalues and eigenvectors, Singuar Value Decomposition (SVD)|

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
|`scikit-learn`|  `conda install -c conda-forge scikit-learn`|

5. To open the notbooks, run `jupyter notebook` in the terminal (or `Anaconda Prompt` in Windows) while the `ml_course` environment is activated.