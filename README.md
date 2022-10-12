# Boom Bikes Demand Analysis¶

> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Code](#code)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
> Business Goal: 
- The company needs to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- <a href="https://github.com/tejasvygunturu/Boom_Bikes_Demand_Analysis/blob/main/day.csv">Dataset</a>

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Analysis is carried out using a Mixed Feature Selection Approach
- 15 features are selected algorithmically using Recursive Feature Elimination. Further selection is done manually by looking at multicollinearity and statistical significance of features and overall fit of the model.
- The 10 most significant features to understand demand have been reported.
- Final Model built on training data set explains 84% of the variability and achieves 79% on test data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Scikit-Learn
- Matplotlib
- Numpy
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Code 
- You can find my Code [here](/Boom_Bikes_Demand_Analysis.ipynb).


## Contact
Created by [@tejasvygunturu](https://github.com/tejasvygunturu) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
