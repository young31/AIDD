# AIDD
https://aiddatathon.com/
- 1st prize winner
- if available, entire codes will be distributed (without data)
![image](https://user-images.githubusercontent.com/50350197/143813919-5e731af2-0e11-4a5d-8490-ceab96d0df7b.png)

## Features
- Most importnat part (we use about 4/6 days)
- Initial time
  - add diverse index feature
- after mid
  - remove redundant and only 24 columns
  - adding some other features harm test score

## Models
- LGB ensemble + Perceiver
- add Perceiver output with nn_weight

### LGB
- use bayes-opt
- use 5 different seed and sum output
 
### Perceiver
- edit repo for our task [here](https://github.com/esceptico/perceiver-io)
- it is not intended to tabular data, we get better results than other our baseline

## ETC
### Models
- Gating network
- Gating Residual network
- xgb / catboost
