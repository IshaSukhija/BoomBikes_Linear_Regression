# BoomBikes_Linear_Regression
Linear Regression model case study for Boom Bikes

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
BoomBikes is US based bike sharing service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.They aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. 
They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Aim of the case study
To understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Data set is given for year 2018 and 2019 to analyse and predict.


## Conclusions

- Top influencing feature is 'weathersit_Light Snow' followed by 'year', 'season_Spring' and 'atemp'.
- Model is build using a Mixed Approach. 18 features are selected sing Recursive Feature Elimination.Further selection is done manually by looking at multicollinearity and statistical significance of features and overall fit of the model.
- The 11 most significant features to understand demand are:
  year     	            1.049202
  atemp                	0.439435
  weekday_Saturday	    0.293324
  month_September     	0.252105
  workingday	          0.241920
  season_Winter	        0.178074
  windspeed	           -0.096158
  month_July	         -0.291617
  weathersit_Mist + Cloudy	-0.370485
  season_Spring       -0.525270
  weathersit_Light Snow	-1.274991
-  The data set is randomly divided into training and test data in 70 and 30 ratio respectively.
-  Final Model is explaining 83% of the variance in data.Model is successfully able to predict at 81% variance in data.
-  For scaling the variables, standard scaling is used.
-  The final relationship between target and predictors is as follows.

𝑐𝑜𝑢𝑛𝑡=−0.49188+1.049202×𝑦𝑒𝑎𝑟+0.439435×𝑎𝑡𝑒𝑚𝑝−1.274991×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡𝐿𝑖𝑔ℎ𝑡𝑆𝑛𝑜𝑤−0.525270×𝑠𝑒𝑎𝑠𝑜𝑛𝑆𝑝𝑟𝑖𝑛𝑔−0.370485×𝑤𝑒𝑎𝑡ℎ𝑒𝑟𝑠𝑖𝑡𝑀𝑖𝑠𝑡+𝐶𝑙𝑜𝑢𝑑𝑦+0.293324×𝑤𝑒𝑒𝑘𝑑𝑎𝑦𝑆𝑎𝑡𝑢𝑟𝑑𝑎𝑦−0.291617×𝑚𝑜𝑛𝑡ℎ𝐽𝑢𝑙𝑦+0.252105×𝑚𝑜𝑛𝑡ℎ𝑆𝑒𝑝𝑡𝑒𝑚𝑏𝑒𝑟+0.241920×𝑤𝑜𝑟𝑘𝑖𝑛𝑔𝑑𝑎𝑦+0.178074×𝑠𝑒𝑎𝑠𝑜𝑛𝑊𝑖𝑛𝑡𝑒𝑟−0.096158×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑

## Technologies Used
- python 3.0
 
## Acknowledgements
- This project was a problem statement given by IIIT-B for the cohort course of ML-AI.


## Contact
Created by [@IshaSukhija] - feel free to contact me!
