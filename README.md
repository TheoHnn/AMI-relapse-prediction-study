# AMI-relapse-prediction-study
A part of the study of the prediction of relapse after an acute myocardial infarction (AMI).
This file is focusing on the unsupervised learning algorithm (PCA) to determine if :
- based on endobiogenical indexes and other physiological features, a clusterization of people could be made.

<br>

----------------

# 🤖 Git specificities 

This repo does not include all the necessery files and functions to work properly as some of them are under the 
intelligence property of the company I used to work under.
It only describes in a very broad way how this part was done and below is the architecture of the working repo.

| File name                               | Description                                                                                                |
|-----------------------------------------|------------------------------------------------------------------------------------------------------------|
| List Functions                          | Agregate all the files needed to run the Machine Learning pipeline, all the libraries and the variables.   |     
| General Functions                       | Functions that have a global purpose such as saving a dataframe or finding a file.                         |
| Indexes                                 | Functions to calculate all the NUMA's index in their raw or ponderated version.                            |
| Preprocessing                           | List of functions to preprocess the data such as handling missing values, outliers etc.                    |
| Statistics                              | List of functions to calculate somes statistical tests.                                                    |
| Training                                | List of functions to train a machine learning model in a supervised or unsupervised way.                                    |
| Visualization                           | List of functions to see any kind of plots and to interpret them easily.                                                                 |
| NotPipelineFunctions                    | Folder that store files that are not related to Machine Learning such as User Interface.                   |

<br>

# 📋 How to Use
## Environment Requirements

**IDE**  : that can open the files (I used VS Code)
**[Python 3.10](https://www.python.org/downloads/)**
**required libraries** : run the following code in a cell of your .ipynb file.
```cmd
pip install -r requirements.txt
```

<br>


----------------

# 📖 Pipeline Organization

***AS IT IS ONLY A PART OF THE WHOLE WORK PLEAE NOT THAT SOME OF THE BELOW STEPS ARE NOT REPRESENTED IN THE CODE***

## Part 1: Exploratory data analysis
- Visualization of the distribution data thanks to different kind of plots such as density, pairwise, etc.
- Visualization of the correlation of data based on plots such as heatmap, etc.
- Statisticals tests based on different assumptions on the normality and homoscedasticity.
    
## Part 2: Preprocessing
- Removing unwanted data such as too old people, etc. 
- Handling outliers 
- Normalizing the data's distribution

## Part 3: Training of the machine learning models
- Splitting data with Train-Test-Verification sets 
- Tuning the hyperparameters of the model and doing a cross validation on the train and test sets
- 
  
## Part 4: Verification of the training
- Checking if the learning was good enough based on metrics
- Plotting graphs to see the behaviour of the model such as Learning curves
- Challenging the model on unseen data withe the verification subset

## Part 5: Error Analysis
- Doing statistical work on the results 
- Plotting graphs to see if a tendency is appearing in the wrong or correct prediction

<br>
