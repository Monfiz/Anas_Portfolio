# Project 1: Movie Clustering and Movie Revenue Prediction

This project is based on the code made for the final project of the master’s course of Data Mining at ITAM, in collaboration with my classmates and friends [AdrianTJ](https://github.com/AdrianTJ), [ro-juja](https://github.com/ro-juja), [mig-calval](https://github.com/mig-calval) and [nelsonalejandrov](https://github.com/nelsonalejandrov). 

This project is subdivided into two. The first part (and the biggest one) is an **unsupervised machine learning algorithm** that makes **clusters** of movies to make recommendations that are similar to an specific movie. The second one is a predictor of how much revenue a movie will make. For this second problem I use several models like **nearest neighbor**, **decision tree**, **random forest**, **linear regression** and more.

Both problems make use of the [Movies Data set](https://www.kaggle.com/rounakbanik/the-movies-dataset?select=ratings.csv) found in Kaggle. Unfortunately the data is to heavy to upload it here. If you would like to see an exploration of the data preview to the modeling you can go to the [EDA folder]().  

## Movie recommendations - Clustering 

### Problem description:

On this first problem we pretend to be a consulting company that seeks to develop an algorithm that recommends movies to new users. This a real life problem that many companies face. 

* Objective: recommend movies that are similar to an specific movie
* Strategy: use different kinds of clusterings by using different kind of metrics and hyper-parameters and combining at the end the recommendations of all the different algorithms. 

## Movie Revenue Predictor - Regression 

### Problem description:

On this second one we pretend to be also a consulting company facing the request of a client that wants to know how to make a profitable movie. 

* Objective: make a predictions of how much revenue a movie will have based on its characteristics. 

* Strategy: To solve the problem, we seek to know which are the most successful movies and make an analysis of the qualities that a good movie has. We want to do analysis and models based on directors, budget, genre, duration and language, as some examples of variables of interest, to predict final profits.


## Files:

* [recomendador_de_peliculas.ipynb](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/recomendador_de_peliculas.ipynb) : This is the main file of the movie recommender  algorithms. This is the most extensive file with more content. 
* [Modelos_Tuning.ipynb](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/Modelos_Tuning.ipynb): Is the main file of the models for the problem of revenue prediction. Here you can find iplementations of models like K-nearest neightbors, Regression with Lasso, Descicion tree, Random forest (best performace),  this algorithms perfomed well, but we also tried some that didnt gave good results like multilayer perceptron and support vector regression.  
* [Importancia.ipynb](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/Importancia.ipynb): After finding the best model we wanted to know witch variables were the most important to the model. So we could give a recommendation to our "client" on witch aspects to focus. This importance analysis is shown on this notebook. 

On the [EDA](https://github.com/Monfiz/Alex_Portfolio/tree/main/Project_1/EDA) folder you can find the files used to explore the data sets. 

## Libraries:



## References:
