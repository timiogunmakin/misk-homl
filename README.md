<img src="https://user-images.githubusercontent.com/6753598/86978801-c3cf3280-c14d-11ea-822a-7e65a384ed8b.png" align="right" width="25%" height="25%"/>

Hands-on machine learning for predictive analytics
================

### Misk Academy

-----

:spiral_calendar: October, 2020  
:alarm_clock:     16:00 - 18:00 & 18:30 - 20:30

-----

## Overview

Students will learn many of the most common machine learning methods to include:

-	A proper modeling process 
-	Feature engineering
-	Linear and logistic regression 
-	Regularized models 
-	K-nearest neighbors 
-	Random forests 
-	Gradient boosting machines 
-	Stacking / super learners 
-	And more!

This module will teach students how to build and tune these various models with R and Python packages that have been tested and approved due to their ability to scale well (i.e. glmnet, ranger, xgboost, h2o, scikit-learn). However, the motivation in almost every case is to describe the techniques in a way that helps develop intuition for its strengths and weaknesses. 

## Learning Objectives

This module will step through the process of building, visualizing, testing, and comparing supervised models. The goal is to expose you to building machine learning models using a variety of algorithms. By the end of this module you should:

* Understand how to apply an end-to-end modeling process that allows you to find an optimal model.
* Be able to properly pre-process your feature and target variables.
* Interpret, apply and compare today's most popular and effective machine learning algorithms.
* Methodically and efficiently tune these algorithms.
* Visualize and compare how features impact these models.

## Prework

This module makes a few assumptions of your established knowledge regarding your programming skills and exposure to basic statistical concepts. Below are my assumptions and the relevant courses that you should have already attended to make sure you are properly prepared. The material provides examples in both R and Python so as long as you are proficient with the assumptions below for one language then you will be good to go.

| Assumptions                       | Resource      
| --------------------------------- | :-------------: |
| Comfortable with R & Python programming    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Proficient with basic data wrangling tasks    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Knowledgable of foundational statistics    | [link](https://github.com/misk-data-science/misk-stats-foundations) |

Prior to session 1, please run the following scripts to ensure you have the necessary packages used throughout. 

| Language                       | Requirements     
| ------------------------------ | :-------------: |
| Python    | [link]() | 
| R    | [link](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/00-setup.Rmd) | 

## Schedule


| Session       | Description                          | Reading(s)    | Slides        | Source code             
| :-----------: | :----------------------------------- | :-----------: | :-----------: | :-----------: |
| 1             | Introduction to machine learning     | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/01-introduction.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/01-introduction-slides.html)  | [[R]](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/01-introduction.Rmd) [[Python](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/01-introduction.ipynb)]  |
| 2             | The modeling process                 | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/02-modeling-process.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/02-modeling-process-slides.html)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/02-modeling-process.Rmd)] [[Python](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/02-modeling-process.ipynb)]  |
| 3             | Feature and target engineering       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/03-engineering.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/03-engineering-slides.html)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/03-feature-engineering.Rmd)] [[Python](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/03-engineering.ipynb)] |
| 4             | __Portfolio builder #1__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x1-portfolio-builder.html)  |   |  |
| 5             | Linear regression                    | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/04-linear-regression.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/04-linear-regression-slides.html)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/04-linear-regression.Rmd)] [[Python](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/04-linear-regression.ipynb)] |
| 6             | Logistic regression                  | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/05-logistic-regression.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/05-logistic-regression-slides.html) | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/05-logistic-regression.Rmd)] [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/05-logistic-regression.ipynb) |
| 7             | Regularized regression               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/06-regularized-regression.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/06-regularized-regression-slides.html) | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/06-regularized-regression.Rmd)] [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/06-regularized-regression.ipynb) |
| 8             | __Portfolio builder #2__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x2-portfolio-builder.html)  |   |  |
| 9             | Multivariate adaptive regression splines | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/07-mars.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/07-mars-slides.html) | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/07-mars.Rmd)]  [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/07-mars.ipynb) |
| 10            | K-nearest neighbors                  | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/08-knn.html)  |  [HTML](https://misk-data-science.github.io/misk-homl/docs/08-knn-slides.html) | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/08-knn.Rmd)]   [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/08-knn.ipynb) |
| 11            | Decision trees                       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/09-decision-trees.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#1)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/09-decision-trees.Rmd)]   [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/09-decision-trees.ipynb) |
| 12            | Bagging                              | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/10-bagging.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#28)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/10-bagging.Rmd)]   [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/10-bagging.ipynb)  |
| 13            | Random forests                       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/11-random-forests.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#36)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/11-random-forests.Rmd)]   [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/11-random-forests.ipynb)   |
| 14            | __Portfolio builder #3__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x3-portfolio-builder.html)  |   |  |
| 15            | Gradient boosting                    | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/12-gbm.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/12-gbm-slides.html)  | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/12-gbm.Rmd)] [[Python]](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/12-gbm.ipynb)   |
| 16            | Stacked models & AutoML              | [Notebook](https://misk-data-science.github.io/misk-homl/docs/notebooks/13-stacked.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/13-stacked-slides.html) | [[R](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/13-stacking.Rmd)] [[Python](https://github.com/misk-data-science/misk-homl/blob/master/materials/Python/13-stacked.ipynb)] |
| 17            | __Portfolio builder #4__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x4-portfolio-builder.html)  |   |   |
