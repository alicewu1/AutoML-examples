# AutoML-examples
**HHA 507 / Data Science / Assignment 9 / Auto ML**


# This repo aims to:
- using SPARCS dataset to conduct 2 experiments using the autoML package ***mljar-supervised***
- Experiment 1: focused around classification (binary or multi-class outcome variable)
- Experiment 2: focused around regression (continuous outcome variable)

### Dataset Used: [Modified SPARCS](https://raw.githubusercontent.com/hantswilliams/HHA-507-2022/main/autoML/datasets/data_sparcs.csv) 



# Experiment 1: Classification (Binary)
- This experiment focused around classification using a binary variable
- Dependent Variable Tested: Race 
- Best Model: **XgBoost**
-     Comparing Log-loss: Lower log loss means better predictions 
        -   Baseline: 1.0208
        -   Decision Tree: 0.631893
        -   XgBoost: 0.824643
        -   Neural Network: 0.795246
        -   Random Forest: 0.768391
        -   RMSE (root-mean-square-deviation)
        -   AUC (Receiver operating characteristic)
- Compared to Baseline, the best model performed **better** because it has a lower log-loss
- Outputs included in folder

<br>

# Experiment 2: Regression (Continuous Outcome Variable)
- This experiment focused around a continuous outcome variable
- Dependent Variable Tested: Total Charges 
- Best Model: **Ensemble**
-     Comparing Log-loss: Lower log loss means better predictions 
        -   Baseline: 1.09861
        -   Decision Tree: 1.50006
        -   XgBoost: 0.376001
        -   Neural Network: 0.404506
        -   Random Forest: 0.217595
        -   Ensemble: 0.216842
- Compared to Baseline, the best model performed **better** because it has a lower log-loss
- Outputs included in folder
