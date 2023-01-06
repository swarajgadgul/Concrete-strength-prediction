# Concrete-strength-prediction

<p align="center">
  <img src="https://github.com/swarajgadgul/Concrete-strength-prediction/blob/main/concrete.jpg" />
</p>



## Problem Statement :

<p>The quality of concrete is determined by its compressive strength, which is measured using a conventional crushing test on a concrete cylinder. The strength of the concrete is also a vital aspect in achieving the requisite longevity. It will take 28 days to test strength, which is a long period. So, what will we do now? We can save a lot of time and effort by using Data Science to estimate how much quantity of which raw material we need for acceptable compressive strength</p>

[View notebook here](https://nbviewer.org/github/swarajgadgul/Concrete-strength-prediction/blob/main/concrete.ipynb)

### Domain: Infrastructure


### Insights:
- Cement is directly proprtional to Compressive strength.
- Addition of adequate amount of  in concrete mixture shows significant increased strength, beyond that strength is reducing.
- Fly ash can be added in certain amount to improve strength.
- Compressive strength is gradually increasing with respect to age. after certain time period,strenght started decreasing.

## Best ML model results:

**Best Model: Random Forest**


|RF Training score| 0.99|
|-----------------|-----|
|RF Test score    | 0.91|
|RF R2 score      | 0.91|
|RF MSE           |25.65|
|RF MAE:          |3.53 |


