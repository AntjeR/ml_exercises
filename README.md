# Machine Learning Exercises

This repository is a modification of an exercise from the Python programming exercises accompanying the theory from Franzis [machine learning book](https://franziskahorn.de/mlbook/). They are part of the curriculum of the [ML for Data Scientists](https://franziskahorn.de/mlws_scientist.html) and [ML in Practice](https://franziskahorn.de/mlws_practice.html) Workshops.


### Using Python

The programming exercises are written in Python. If you're unfamiliar with Python, you should work through [this tutorial](https://github.com/cod3licious/python_tutorial) first.


#### Working in the cloud

If you are unable to install Python on your own computer, you can run the notebooks in a cloud environment.


##### Using MyBinder

The easiest way to run the notebooks is using MyBinder:
[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AntjeR/ml_exercises/HEAD?labpath=Decison_Trees_In_Practice.ipynb) <br>

However, please note that MyBinder may take a while to load and some notebooks might be slow or even crash due to insufficient RAM. Furthermore, by default this environment does not include the necessary libraries to run notebook 6, since installing the neural network dependencies takes very long.


##### Using Google Colab

If you have a Google account, you can also run the  in Google Colab, which is faster than MyBinder:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AntjeR/ml_exercises/blob/main/Decison_Trees_In_Practice.ipynb) <br>

While Google Colab already includes most packages that we need, should you require an additional library you can install a package by executing `!pip install package` in a notebook cell. With Colab, it is also possible to run code on a GPU, but this has to be manually selected.

#### Working on your own computer
The [Python tutorial](https://github.com/cod3licious/python_tutorial) includes some notes on how to install Python and Jupyter Notebook on your own computer. <br>
Please make sure you're using Python 3 and all libraries listed in the [`requirements.txt`](/requirements.txt) file are installed and up to date.

