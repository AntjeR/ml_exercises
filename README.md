# Machine Learning Exercises

This repository contains the exercises accompanying the theory from my [machine learning book](https://franziskahorn.de/mlbook/).

If you have any questions, please send me an [email](mailto:hey@franziskahorn.de).

Have fun!

### Using Python

The programming exercises are written in Python. If you're unfamiliar with Python, you should work through [this tutorial](https://github.com/cod3licious/python_tutorial) at the beginning of the course.

##### Using Python on your own computer
The [Python tutorial](https://github.com/cod3licious/python_tutorial) includes some notes on how to install Python and Jupyter Notebook on your own computer. <br>
Please make sure you're using Python 3 and all libraries listed in the [`requirements.txt`](/requirements.txt) file are installed and up to date. You can verify this with the [`test_installation.ipynb`](/test_installation.ipynb) notebook.

##### Using Google Colab
If you have a Google account, you can also run the code in the cloud using Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cod3licious/ml_exercises) <br>
While Google Colab already includes most packages that we need, should you require an additional library (e.g., `skorch` for training PyTorch neural networks in notebook 5), you can install a package by executing `!pip install package` in a notebook cell. With Colab, it is also possible to run code on a GPU, but this has to be manually selected.


## Course Overview

For an optimal learning experience, the chapters from the [machine learning book](https://franziskahorn.de/mlbook/) should be interleaved with quizzes and programming exercises as shown below. Additionally, you should take notes in the workbook while working through the materials.

**Important:** Please make note of all questions that arise while working through the materials. At the beginning of each group session, we'll collect everyone's questions and discuss them.

You can also find the course syllabus on the last page of the [course description](/ml_course_description.pdf), which explicitly lists all the sections of the book for each block.

---

### Part 1: Getting started: What is ML?

##### Block 1.1:
- [ ] Read the whole chapter: ["Introduction"](https://franziskahorn.de/mlbook/_introduction.html)
- [ ] Answer [Quiz 1](https://forms.gle/uzdzytpsYf9sFG946)

##### Block 1.2:
- [ ] Read the whole chapter: ["ML with Python"](https://franziskahorn.de/mlbook/_ml_with_python.html)
- [ ] Install Python on your computer and complete the [Python tutorial](https://github.com/cod3licious/python_tutorial)

##### Block 1.3:
- [ ] Read the whole chapter: ["Data & Preprocessing"](https://franziskahorn.de/mlbook/_data_preprocessing.html)
- [ ] Answer [Quiz 2](https://forms.gle/Pqr6EKHNxzrWb7MF9)

##### Block 1.4:
- [ ] Read the whole chapter ["ML Solutions: Overview"](https://franziskahorn.de/mlbook/_ml_solutions_overview.html)
- [ ] Answer [Quiz 3](https://forms.gle/fr7PYmP9Exx4Vvrc8)
- [ ] Prepare a [90-second Spotlight presentation](/exercise_ml_use_cases_spotlight.pdf) for one of the given ML use cases

---

### Part 2: Your first algorithms

##### Block 2.1:
- [ ] Read the whole chapter: ["Unsupervised Learning"](https://franziskahorn.de/mlbook/_unsupervised_learning.html)
- [ ] Work through [Notebook 1: visualize text](/notebooks/1_visualize_text.ipynb) (after the section on dimensionality reduction)
- [ ] Work through [Notebook 2: image quantization](/notebooks/2_image_quantization.ipynb) (after the section on clustering)

##### Block 2.2:
- [ ] Read the first sections of the chapter ["Supervised Learning"](https://franziskahorn.de/mlbook/_supervised_learning.html) up to and including ["Model Evaluation"](https://franziskahorn.de/mlbook/_model_evaluation.html)
- [ ] Answer [Quiz 4](https://forms.gle/M2dDevwzicjcHLtc9)

---

### Part 3: Advanced models

##### Block 3.1:
- [ ] Read the remaining sections from the supervised learning chapter, i.e., ["Linear Models"](https://franziskahorn.de/mlbook/_linear_models.html) up to and including ["Kernel Methods"](https://franziskahorn.de/mlbook/_kernel_methods.html)
- [ ] **In parallel**, work through the respective sections of [Notebook 3: supervised comparison](/notebooks/3_supervised_comparison.ipynb)

##### Block 3.2:
- [ ] Start with the chapter ["Deep Learning & more"](https://franziskahorn.de/mlbook/_deep_learning_more.html) up to and including the section: ["Information Retrieval (Similarity Search)"](https://franziskahorn.de/mlbook/_information_retrieval_similarity_search.html) and refresh your memory on the sections on [TF-IDF feature vectors](https://franziskahorn.de/mlbook/_feature_extraction.html) and [cosine similarity](https://franziskahorn.de/mlbook/_computing_similarities.html)
- [ ] Work through [Notebook 4: information retrieval](/notebooks/4_information_retrieval.ipynb)

##### Block 3.3:
- [ ] Read the section: ["Deep Learning (Neural Networks)"](https://franziskahorn.de/mlbook/_deep_learning_neural_networks.html)
- [ ] Work through [Notebook 5: MNIST with torch](/notebooks/5_mnist_torch.ipynb) (recommended) **_or_** [MNIST with keras](/notebooks/5_mnist_keras.ipynb) (in case others in your organization are already working with TensorFlow)

##### Block 3.4:
- [ ] Read the sections: ["Time Series Forecasting"](https://franziskahorn.de/mlbook/_time_series_forecasting.html) and ["Recommender Systems (Pairwise Data)"](https://franziskahorn.de/mlbook/_recommender_systems_pairwise_data.html)

---

### Part 4: Avoiding common pitfalls

##### Block 4.1:
- [ ] Read the whole chapter: ["Avoiding Common Pitfalls"](https://franziskahorn.de/mlbook/_avoiding_common_pitfalls.html)

##### Block 4.2:
- [ ] Work through [Notebook 6: analyze toy dataset](/notebooks/6_analyze_toydata.ipynb)
- [ ] Have a look at the [cheat sheet](/cheatsheet.pdf), which includes a summary of the most important steps when developing a machine learning solution, incl. code snippets

##### Block 4.3:
- [ ] _Case Study!_ Work through [Notebook 7: predicting hard drive failures](/notebooks/7_hard_drive_failures.ipynb) (plan at least 5 hours for this!)

---

### Part 5: RL & Conclusion

##### Block 5.1:
- [ ] Read the whole chapter: ["Reinforcement Learning"](https://franziskahorn.de/mlbook/_reinforcement_learning.html)
- [ ] Work through [Notebook 8: RL gridmove](/notebooks/8_rl_gridmove.ipynb)

##### Block 5.2:
- [ ] Answer [Quiz 5](https://forms.gle/uZGj54YQHKwckmL46)
- [ ] Read the whole chapter: ["Conclusion"](https://franziskahorn.de/mlbook/_conclusion.html)
- [ ] Complete the exercise: ["Your next ML Project"](/exercise_your_ml_project.pdf) (in case you need some inspiration for a project idea, have a look at [how ML could be used to fight climate change](https://www.climatechange.ai/summaries)). Feel free to prepare a few slides or use the [Word template](/exercise_your_ml_project_template.docx) and aim for a 5 minute presentation.

---
