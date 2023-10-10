# Bike Sharing Assignment
> BoomBikes wants to understand the factors on which the demand for these shared bikes depends. They want to understand the factors affecting the demand for these shared bikes in the American market.

The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement
BoomBikes wants to understand the factors on which the demand for these shared bikes depends. They want to understand the factors affecting the demand for these shared bikes in the American market.

The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Business Goal
A model to capture the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Post building the model, the best fit line is represented by:

cnt = yr * 0.2384 - holiday * 0.0754 + temp * 0.4233 - windspeed * 0.1398 - season_spring * 0.1286 + season_winter * 0.0681 - mnth_Dec * 0.0501 - mnth_Jul * 0.0791 - mnth_Nov * 0.0650 - weathersit_LightRain_LightSnow_Thunderstorm * 0.2721 - weathersit_Mist_Cloudy * 0.0738

### Evaluation Summary

- Test dataset:
    - R-squared on test dataset = 82.8%
- Train dataset
    - R-squared on training dataset = 82.9%
    - Adjusted R-squared in training dataset = 82.5%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.3
- Pandas - version 1.3.4
- numpy - version 1.21.5
- matplotlib - version 3.1.3
- seaborn - version 0.12.2
- sklearn - version 1.0.2
- statsmodel - version 0.13.2



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@deepakbhadoria] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->