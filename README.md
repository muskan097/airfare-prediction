# Airfare Prediction

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Demo](#demo)
  * [Technical Aspect](#technical-aspect)
  * [Directory Tree](#directory-tree)
  * [Technologies Used](#technologies-used)
 

## Overview
Of all the unanswered questions: How did the life begin? Why do we dream? -  perhaps the greatest is this: flight prices. Buy a ticket one day at some price; buy that same ticket a few days later, it will be a whole different story. Finding the most favorable timing for airline ticket purchasing from the customer's perspective is challenging because buyers have insufficient information for reasoning about future price movements.

Well, this is one question we can solve with data science.

If anyone has an answer to the above questions, I would love to hear from you. Connect with me on Linkedin : [Linkedin](https://linkedin.com/in/muskan-gulati)

## Motivation
The motivation for doing this project was primarily an interest in undertaking a challenging project in an interesting area of research.


## Demo
Link: [https://flightsfareprediction.herokuapp.com/](https://flightsfareprediction.herokuapp.com/)

[![](https://i.imgur.com/cxBPrgt.png)](https://flightsfareprediction.herokuapp.com/)

[![](https://i.imgur.com/p0ZP8xp.png)](https://flightsfareprediction.herokuapp.com/)


## Technical Aspect
The project is divide into four parts:

1.	Data Preprocessing: Observed shape and data type. Converted the features to the right datatype. Observed the summary of statistics pertaining to the DataFrame columns.

    The dataset consisted of missing values. The missing values corresponds to a single row. Therefore, dropped row.

    Extracted day and month from journey date for better prediction.

    Similarly extracted hours and minutes from departure and arrival time and converted to minutes.

    Converted Total_stops from string to numerical value.

2.	Exploratory Data Analysis: analyzed data sets to summarize their main characteristics, with visual methods. Some of the observations are:
    More number of flights operates in the month of May and June.

    Flights Servicing from Bangalore costs more.

    Flights arriving to Delhi has costs more.

    Price increases with increase in number of stops.
	
3.	Training the model: Trained the data on Random Forest. We got R squared value of 0.839 and MAE 1140. Saved the model into pickle file.

4.	Deployment on Heroku: Deployed the model on Heroku platform connecting Github Profile. Followed the instruction given on [Heroku Documentation]      (https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.


    
## Directory Tree 
```
├── static 
│   ├── css
│   ├── images 
├── templates
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── Air Fare prediction.ipynb
├── airfare.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

