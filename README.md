# Clean Water Machine Learning Competition @CentraleSupelec

## General context 

This project is part of a competition at University Paris Saclay, CentraleSupelec Paris. 

Files and descriptions are in French. For general purposes, this readme is the only content in english inside this project so that everyone can understand the context. 

## 📦 The Competition 

Access to safe drinking water is essential to health, a basic human right, and a component of effective policy for health protection. This is important as a health and development issue at a national, regional, and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.

The dataset is available at this link [drinking_water_potability.csv](https://github.com/bidouze/CleanWaterData/blob/main/drinking_water_potability.csv). The file file contains water quality metrics for 3276 different water bodies.

## 🏆 The Model

The reader may look at our approach in the file [Eau potable.ipynb](https://github.com/bidouze/CleanWaterData/blob/main/Eau%20potable.ipynb). This notebook contains data visualization in order to justify feature choices and engineering. We used a nested cross validation to choose the right model for our problem. 

The winning model is an SVM that we finetuned accordingly to the notebook linked above. 


## References 

[1] Lundberg, Scott M and Lee, Su-In, A Unified Approach to Interpreting Model Predictions, Advances in Neural Information Processing Systems 30 (2017)

[2] Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani, An introduction to stastical learning, Springer

[3] Friedman, Jerome H., The elements of statistical learning: Data mining, inference, and prediction, Springer
