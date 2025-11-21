# Current progress and applied work:
some mark:
- X: done
- /: have started, not yet done
- ?: I don't know what to do with it
## Task1
Data Cleaning: replace missing value using MICE imputer
Model: CatBoost
Done: 
- Add Grid Search
- Select most optimize imputer(??)

To-do: 
- [ ]feature selection
- [ x ]in-dept cleaning
- [ x ]Deal with imbalance data?
- [ x ]hyperparameter and fine-tuning
- [ x ]select the model

## Task2
Data Cleaning: replace missing number using MICE imputer and category using ffill/bfill and mean to filled null value
Model: CatBoost

To-do:
- [ ]class imbalance 
- [ ]feature selection
- [ x ]refine model
- [ x ]format the text/notebook

## Task3
Data Cleaning: MICE for numerical and mode for categorical
Model: Randomforest and XGBoost 
Done:
- zero-inflated model: now the model can predict zero
- refine cleaning process

To-do:
- [ x ]zero-inflated data
- [ x ]log transformation
- [ ]feature engineering
- [ x ]applied more advance model

## Task4
Data Cleaning: is there need to?
Model: VGG?

To-do:
- []fine-tune the parameter/try train it on more powerful cpu
- []ensemble method
- []class imbalance?
- []try pre-train model

## Task5
Data Cleaning: also using MICE
Model: Isolation Forest

To-do:
- [ x ]Try using ensemble or other model
- []clean data