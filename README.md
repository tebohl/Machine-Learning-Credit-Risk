# Machine-Learning-Credit-Risk

## Description:
I built two machine learning models that attempt to predict whether a loan will be approved or not based on the data in lending_data.csv.

## Methods/tools:
- Python/Pandas
- Scikit learn

## Prediction
I predicted that the logistical regression will perform better. Based on the material presented to me, it is ideal to try logistic regression first to see how it does, and often a simpler model is "good enough" and should be used when applicable and minimal data preprocessing is needed. 

## Process
After importing and previewing the data from the Resources folder, I trained a Logisitic Regression model which yieled a testing data score of ~0.9918. Then, I scaled the data and trained a Random Forest Classifer model which yielded a testing score of ~0.99107. The scores are very close and it seems either model could be suitable. I included some additional exploration of the models in my notebook as well.