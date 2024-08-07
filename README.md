# AQI Meter ☁

## Disclaimer
> This is a **COPY** of the original repository which is under my partner's GitHub page linked here: https://github.com/ved-tiwari/AQI-Meter

## Description
> View air quality, pollen, and weather statistics in 190+ countries. Designed to be easy to use for those who are interested in learning the air quality statistics in any city in the world.

## About the project
![Screenshot 2021-03-27 190439](https://user-images.githubusercontent.com/79772110/112737254-696e4000-8f2f-11eb-916f-4d9bbe2e3928.png)
> As time progresses, our air quality continues to worsen at an ever alarming rate. Many factories and vehicles are emitting thousands of tons of emissions in the air and people  who are living in places with more air pollution are suffering as a result. Myself and many others are concerned about the ongoing air quality issue. I was motivated to create  this project because I noticed that there is not enough consolidated data that presents both pollutants and pollen markers in one app.
> 
> AQI Meter features a suite of unique features bundled in one software application which is unlike any other program
> 
> Here are just a few special features AQI Meter has to offer:
> 
<ul>
  <li>
    Air quality information mapped on the globally used AQI (Air Quality Index) scale
  </li>
  <li>
    Health reccomendations tuned to the AQI value in the given area
  </li>
  <li>
    Individual pollutant concentrations including PM<sub>2.5</sub>, O<sub>3</sub>, PM<sub>10</sub>, and many more
  </li>
  <li>
    Weed, Tree, and Grass pollen concentrations
  </li>
  <li>
    AQI predictions for the next 6 hours using machine learning algorithms
  </li>
  <li>
    Weather informationin the given city including temperature, and precipitation, etc.
  </li>
  <li>
    Accurate information for almost every city in the world
  </li>
</ul>

## Machine Learning
> AQI Meter uses a linear regression algorithm to predict future AQI values. The historical data for the past 17 hours is sent to the python backend via an AJAX call. Afterwords, the scikitlearn module for python predicts future air quality values for the next 6 hours. Then using jinja syntax provided with flask, the predictions are sent back to JavaScript to chart the data using the chartjs library.

## Built With
<ul>
  <li>
    HTML/CSS/JavaScript
  </li>
  <li>
    chartJs
  </li>
  <li>
    jQuery
  </li>
  <li>
    Bootstrap
  </li>
  <li>
    Jinja
  </li>
  <li>
    Flask framework (Python)
  </li>
  <li>
    SciKitLearn Module
  </li>
  <li>
    Numpy Module
  </li>
</ul>
