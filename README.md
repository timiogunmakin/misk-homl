<img src="https://user-images.githubusercontent.com/6753598/86978801-c3cf3280-c14d-11ea-822a-7e65a384ed8b.png" align="right" width="25%" height="25%"/>

Hands-on machine learning for predictive analytics
================

### Misk Academy

-----

:spiral_calendar: September XX-XX, 2020  
:alarm_clock:     09:00 - 17:00  
:hotel:           TBD  
:writing_hand:    TBD

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

This module makes a few assumptions of your established knowledge regarding your programming skills and exposure to basic statistical concepts. Below are my assumptions and the relevant courses that you should have already attended to make sure you are properly prepared. Most of the material is heavily focused on R implementations; however, we also provide and link to many Python implementations. Consequently, the R assumptions are strong but the Python requirements are not firm.

| Assumptions                       | Resource      
| --------------------------------- | :-------------: |
| Comfortable with R & Python programming    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Proficient with basic data wrangling tasks    | [link](https://github.com/misk-data-science/misk-intro-ds) | 
| Knowledgable of foundational statistics    | [link](https://github.com/misk-data-science/misk-stats-foundations) |

Prior to session 1, please run the [`00-setup.Rmd` notebook](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/00-setup.Rmd) to ensure you have the necessary packages used throughout.

## Schedule

Most of the material is heavily focused on R implementations; however, the language to implement modeling is less important than gaining strong intuition behind what the algorithms are doing. Furthermore, you should strive to feel comfortable implementing these algorithms in both languages. Therefore, in each notebook we provide examples and resources to illustrate Python implementations. Moreover, we offer **_Python challenges_** that will challenge you with implementing the modeling algorithms and processes in Python.

| Session       | Description                          | Reading(s)    | Slides        | Source code             
| :-----------: | :----------------------------------- | :-----------: | :-----------: | :-----------: |
| 1             | Introduction to machine learning     | [Notebook](https://misk-data-science.github.io/misk-homl/docs/01-introduction.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/01-introduction-slides.html)  |    |
| 2             | The modeling process                 | [Notebook](https://misk-data-science.github.io/misk-homl/docs/02-modeling-process.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/02-modeling-process-slides.html)  | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/02-modeling-process.Rmd)   |
| 3             | Feature and target engineering       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/03-engineering.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/03-engineering-slides.html)  | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/03-feature-engineering.Rmd) |
| 4             | __Portfolio builder #1__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x1-portfolio-builder.html)  |   |  |
| 5             | Linear regression                    | [Notebook](https://misk-data-science.github.io/misk-homl/docs/04-linear-regression.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/04-linear-regression-slides.html)  | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/04-linear-regression.Rmd) |
| 6             | Logistic regression                  | [Notebook](https://misk-data-science.github.io/misk-homl/docs/05-logistic-regression.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/05-logistic-regression-slides.html) | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/05-logistic-regression.Rmd)  |
| 7             | Regularized regression               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/06-regularized-regression.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/06-regularized-regression-slides.html) | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/06-regularized-regression.Rmd) |
| 8             | __Portfolio builder #2__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x2-portfolio-builder.html)  |   |  |
| 9             | Multivariate adaptive regression splines | [Notebook](https://misk-data-science.github.io/misk-homl/docs/07-mars.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/07-mars-slides.html) | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/07-mars.Rmd) |
| 10            | K-nearest neighbors                  | [Notebook](https://misk-data-science.github.io/misk-homl/docs/08-knn.nb.html)  |  [HTML](https://misk-data-science.github.io/misk-homl/docs/08-knn-slides.html) | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/08-knn.Rmd) |
| 11            | Decision trees                       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/09-decision-trees.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#1)  |    |
| 12            | Bagging                              | [Notebook](https://misk-data-science.github.io/misk-homl/docs/10-bagging.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#28)  |    |
| 13            | Random forests                       | [Notebook](https://misk-data-science.github.io/misk-homl/docs/11-random-forests.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/09-dt-bagging-rf-slides.html#36)  | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/11-random-forests.Rmd)   |
| 14            | __Portfolio builder #3__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x3-portfolio-builder.html)  |   |  |
| 15            | Gradient boosting                    | [Notebook](https://misk-data-science.github.io/misk-homl/docs/12-gbm.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/12-gbm-slides.html)  | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/12-gbm.Rmd)   |
| 16            | Stacked models & AutoML              | [Notebook](https://misk-data-science.github.io/misk-homl/docs/13-stacked.nb.html)  | [HTML](https://misk-data-science.github.io/misk-homl/docs/13-stacked-slides.html) | [.Rmd](https://github.com/misk-data-science/misk-homl/blob/master/materials/R/13-stacking.Rmd) |
| 17            | __Portfolio builder #4__               | [Notebook](https://misk-data-science.github.io/misk-homl/docs/99x4-portfolio-builder.html)  |   |   |
