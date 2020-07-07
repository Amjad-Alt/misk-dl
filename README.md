Deep Learning with Keras and TensorFlow
================

### Misk Academy

-----

:spiral_calendar: September XX-XX, 2020  
:alarm_clock:     09:00 - 17:00  
:hotel:           TBD  
:writing_hand:    TBD

-----

## Overview

This module introduces the essential concepts of building deep learning models with TensorFlow and Keras. Throughout this module students will gain an intuitive understanding of the architectures and engines that make up deep learning models, apply a variety of deep learning algorithms (i.e. MLPs, CNNs, RNNs, LSTMs, collaborative filtering), understand when and how to tune the various hyperparameters, and be able to interpret model results. Students will have the opportunity to apply practical applications covering a variety of tasks such as computer vision, natural language processing, product recommendation and more. By the end of this module, students should have a firm grasp of deep learning and be able to implement a systematic approach for producing high quality modeling results.

## Learning Objectives

This module will step through the process of building, visualizing, testing, and comparing common deep learning models. The goal is to expose you to building various deep learning models for common problems where deep learning tends to shine. By the end of this module you should:

* Have an intuitive understanding of the engines and architectures that drive deep learning.

* Be ale to apply a variety of deep learning algorithms.

* Established a mental model of deep learning.

## Prework

This module makes a few assumptions of your established knowledge regarding your programming skills and exposure to basic statistical concepts. Below are my assumptions and the relevant courses that you should have already attended to make sure you are properly prepared.

| Assumptions                       | Resource      
| --------------------------------- | :-------------: |
| Comfortable with R programming    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Proficient with basic data wrangling tasks    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Knowledgable of foundational statistics    | [link](https://github.com/misk-data-science/misk-stats-foundations) |
| familiar with the machine learning modeling process | [link](https://github.com/misk-data-science/misk-homl) |

Prior to session 1, please run the [`001-requirements.Rmd` notebook](https://github.com/misk-data-science/misk-dl/blob/master/materials/01-intro/01-requirements.md) to ensure you have the necessary packages and data assets used throughout.

## Schedule

This workshop is notebook-focused. Consequently, most of our time will be spent in R notebooks; however, I will also jump to slides to explain certain concepts in further detail. Throughout the notebooks, you will see ℹ️ icons that will hyperlink to relevant slides (or additional resources).

| Session       | Description                          | Notebook    | Source code    | Other       
| :-----------: | :----------------------------------- | :-----------: | :-----------: | :-----------: |
| 1             | Introduction to deep learning and deep learning ingredients | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/01-main-ingredients.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/02-main-ingredients/01-main-ingredients.Rmd) | [Slides](https://misk-data-science.github.io/misk-dl/01-introduction-slides.html)     | 
| 2             | Approaching deep learning model development                 | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/02-starter-recipe.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/03-recipe/01-starter-recipe.Rmd) | TBD           |
| 3             | __Portfolio builder__: Predicting Ames, IA home sales prices    | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/03-mini-project-ames.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/03-recipe/02-mini-project-ames.Rmd) |            | 
| 4             | Introduction to Computer vision and CNNs                    | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/04-mnist-revisited.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/04-computer-vision-CNNs/01-mnist-revisited.Rmd) | TBD           |
| 5             | Image generators & augmentation                             | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/05-cats-vs-dogs.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/04-computer-vision-CNNs/02-cats-vs-dogs.Rmd) | TBD           |
| 6             | Transfer learning for CNNs                                  | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/06-transfer-learning.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/04-computer-vision-CNNs/03-transfer-learning.Rmd) | TBD           |
| 7             | __Portfolio builder__: Classifying natural images               | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/07-mini-project-cnn.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/05-project/01-Project.Rmd) |            |
| 8             | Introduction to word embeddings                             | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/08-word-embeddings.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/06-word-embeddings/01-word-embeddings.Rmd) | TBD           |
| 9             | Pre-trained word embeddings                                 | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/09-pretrained-word-embeddings.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/06-word-embeddings/02-pretrained-word-embeddings.Rmd)  | TBD           |
| 10            | __Portfolio builder__: Product reviews                          | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/10-mini-project-amazon-word-embeddings.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/06-word-embeddings/03-your-turn-amazon-word-embeddings.Rmd)  |            |
| 11            | Collaborative filtering                                     | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/11-collaborative-filtering.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/07-recommender-collaborative-filtering/collaborative-filtering.Rmd) | TBD           |
| 12            | Introduction to RNNs & LSTMs                                | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/12-intro-to-lstms.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/08-NLP-LSTMs/01-intro-to-lstms.Rmd)  | TBD           |
| 13            | __Portfolio builder__: Sentiment polarity with LSTMs            | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/13-mini-project-lstms.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/08-NLP-LSTMs/02-your-turn-lstms.Rmd)  |           |
| 14            | __Portfolio builder__: Detecting duplicate quora questions      | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/14-mini-project-quora.nb.html)  | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/09-project/Final-Project.Rmd) |           |


## Extras

| Activity                      | Notebook | Source Code |
| :---------------------------- | :--------: | :-----------: |
| Improving generalization with k-fold cross validation       | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x1-validation-procedures.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x1-validation-procedures.Rmd) |
| Performing a grid search | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x2-imdb-grid-search.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x2-imdb-grid-search.Rmd) |
| Linear regression with stochastic gradient descent | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x3-manual-gradient-descent.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x3-manual-gradient-descent.Rmd) |
| Diagnosing model performance with learning curves | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x4-learning-curve-diagnostics.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x4-learning-curve-diagnostics.Rmd) |
| Save your models for later with serialization | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x5-save-your-models.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x5-save-your-models-diagnostics.Rmd) |
| Visualizing what CNNs learn | [Notebook](https://misk-data-science.github.io/misk-dl/notebooks/99x6-visualizing-what-cnns-learn.nb.html) | [.Rmd](https://github.com/misk-data-science/misk-dl/blob/master/materials/99-extras/99x6-visualizing-what-cnns-learn.Rmd) |

