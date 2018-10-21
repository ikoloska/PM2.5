# PM2.5
Predicting the level of PM2.5 particles in one of the most polluted cities in Europe

Skopje, the capital of the Republic of Macedonia, is one of the most poluted cities in Europe (check out https://www.dw.com/en/skopje-welcome-to-europes-most-polluted-city/g-42083092 ). In this project, I try to predict the level of PM2.5 particles which can enter the bloodstream and cause heart and lungs issues, by using the level of Carbon Dioxide (CO2), Nitrogen Dioxide (NO2), Trioxygen/Ozone (O3) and PM10 particles.  

# Prerequisites
You will need numpy, pandas, and sklearn.

# Dataset
The data set can be found on https://www.kaggle.com/cokastefan/pm10-pollution-data-in-skopje-from-2008-to-2018. However, it is quite sparse and requires some preprocessing. The measurements are aggregated based on geographical location (I've included an example). The PM2.5 particles are then divided into 20 equaly spaced categories.

# Results
The highest overall prediction accuracy is around 80%, by using a Random Forest Classifier with 100 estimators. More details on RFC can be found on
http://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
https://medium.com/machine-learning-101/chapter-5-random-forest-classifier-56dc7425c3e1
https://en.wikipedia.org/wiki/Random_forest

# Ackgnoligments
Thanks to cokastefan (https://www.kaggle.com/cokastefan) for uploading the dataset to Kaggle.
