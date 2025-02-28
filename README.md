# classification-challenge
# File
spam_detector.jpynb
# Description
This is a small program that imports the data below and constructs logistic regression and random forest models to predict whether an email is spam.  The data is split into test and train splits and standardscaler is applied to the feature data.  Both model types are compared using accuracy scoring.  Optimization of the random forest model was achieved by varying the depth parameter.  It was found the random forest model with a depth of 11 was best.  Based upon this, the confusion matrix, classification report, and area under curve were reviewed for assess model robustness.
# Data source
- https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv
# Dependencies
- pandas
- sklearn.model.selection
- sklearn.metrics
- matplotlib.pyplot
- numpy
#Python version
- 3.12.7
