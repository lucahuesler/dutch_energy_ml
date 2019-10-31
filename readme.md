#  ML group work on dutch energy

For description of the dataset, see: https://www.kaggle.com/lucabasa/dutch-energy



## Task 1

#### Task 1.1

General Formula: 

$$annual\_consume = \beta_0 + \beta1*smartmeter\_perc + [...]$$

- Idea: Try to use smartmeter percentage as a indirect way to consider self production in the 
  model.
- Other predictors may also be considered in the model

#### Task 1.2

General formula:

$$annual\_consume\_low\_tarif = \beta_0 + \beta1*smartmeter\_perc + [...]$$

- Idea: Smart meter steers consumption and tells you when to use which device (e.g. better to use washing machine at night)
- Other predictors may also be considered in the model



For both tasks, we build a linear model and a support vector machine (SVM). We then compare the two models and tune the better model by applying cross validation.

