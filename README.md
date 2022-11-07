# Project Name
> ## Bike Sharing Demand prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. They have decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 

- Essentially, the company wants —

  - Which variables are significant in predicting the demand for shared bikes.
  - How well those variables describe the bike demands

- Based on various meteorological surveys and people's styles, we have a large dataset on daily bike demands across the American market based on some factors. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Have created a model with an accuracy of 81 - 84 % to predict the bike sharing demand prediction
- Based on the model following are the factors which affect the demand both +ve and -ve:
  - year(yr) **+ve**
  - workingday **+ve**
  - temperature(temp) **+ve**
  - humidity(hum) **-ve**
  - windspeed **-ve**
  - season (summer, winter) **+ve**
  - season (spring) **-ve**
  - month (september(sep))  **+ve**
  - weekday (saturday(sat)) **+ve**
  - weather situation (Light Rain/Snow, Misty) **-ve**
- The final linear equation is:
  - count = 0.2176 + 0.2307 * `yr` + 0.053 * `workingday` + 0.5126 * `temp` - 0.1524 * `hum` - 0.1801 * `windspeed` - 0.045 * `spring` + 0.0697 * `summer` + 0.1108 * `winter` + 0.0942 * `sep` + 0.0625 * `sat` - 0.2472 * `Light Rain/Snow` - 0.056 * `Misty`


## Technologies Used
- pandas 1.4.2
- seaborn 0.11.2
- matplotlib 3.5.1
- sklearn 1.0.2
- statsmodel 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is done as part of Execution PG on ML & AI from upgrade with partnership with IIITB
- This project was based on [this tutorial](https://github.com/ContentUpgrad/Linear-Regression/tree/main/Multiple%20Linear%20Regression%20in%20Python).


## Contact
Created by [@vighu0710] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
