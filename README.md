# credit-risk-classification

Code by Ryan Dekker;
I did use the following site as a basis for coding a dataset using the RandomOverSampler module:
    https://imbalanced-learn.org/stable/over_sampling.html

Credit Risk Analysis Report

This model takes existing data and trains a model to assess which features lead to good and bad loans. Of test the model, the X-test and Y-test data split he data, which leaves part of the data set aside to test the model on "new" data. 
  * The model was 97.2% precise at determining which independent variables causes the dependent result - either a good or a bad loan.
  * The model's f1 accuary score was 99% 
  * The recall score for good loans was 99% and for predicting bad loans, it was less effective at 94%

Overall, the model was excellent in predicting which loans would be good loans. It was not quite as accurate in predicting which loans would defualt, which was because the loans that defaulted were a minority, so there are fewer instances to learn what best predicts loans that default. This model did have mostly accurate results and should be used for determining good loans. However, a resampling technique could still improve this model so that more data could be used to best determine which features predict bad loans. 
