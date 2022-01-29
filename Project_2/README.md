
# Project 2: Hotel Cancelations prediction 

This project is based on the code made for the final project of the master’s course of Machine Learning at ITAM, in collaboration with my classmates [marcoyel21]( https://github.com/marcoyel21)  and [joelitam2021]( https://github.com/joelitam2021). 

## Problem description:
To plan rates and sales or promotional activities, hotels make advance estimates of their occupancy on each day. Part of these estimates requires predicting how many of the reservations you already have will end up in cancellations, which frees up inventory that affects planning.

* Objective: Predict which reservations are likely to end in cancellation or not.

* Strategy: Create variables and combinations exhaustively so that models perform feature selection autonomously.

## Files:

* [report.pdf](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/Hotel_cancelations_report_spanish.pdf): on this file you can find the main project, with a brief part of the EDA, feature engineering, lasso regression with cross validation and finally a random forest that gave the best results. This is a pdf rendered if you would like to see the full code you can go to the file [report.Rmd](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/report.Rmd).

* [EDA_hotel_cancelations.Rmd](https://github.com/Monfiz/Alex_Portfolio/blob/main/Project_1/EDA_hotel_cancelations.Rmd): here you can find a more profound exploration of the Data, mainly focused on distributions for canceled reservations and non-canceled ones and a time series analysis of the seasonality. 

* [data]( https://github.com/Monfiz/Alex_Portfolio/tree/main/Project_1/data): on this folder you can find both training and testing sets which come from the cite [Kaggle](https://www.kaggle.com/c/cancelaciones-en-hoteles/data) based on this article [Hotel booking demand data sets](https://www.sciencedirect.com/science/article/pii/S2352340918315191)

## Libraries:

* Tidyverse
* Patchwork
* Ggplot2
* DataExplorer
* Dplyr
* Matrix
* Stringr

## References:

* [Kaggle](https://www.kaggle.com/c/cancelaciones-en-hoteles/data)
* [Hotel](https://www.sciencedirect.com/science/article/pii/S2352340918315191)
* [Series de tiempo](https://es.wikipedia.org/wiki/Serie_temporal)
* [One hot encoding](https://www.educative.io/blog/one-hot-encoding)
* [Ralas Matrix]( http://amunategui.github.io/sparse-matrix-glmnet/)
* [Matrix](https://cran.rproject.org/web/packages/Matrix/index.html)
* [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)
