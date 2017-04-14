# Patent Challenge

The goal of this data challenge was to classify european patents that were granted or rejected. In order to do so, there were around 50 different features available for each patent such as its technology sector or its country.

# Approach
I used the XGBoost classifier to do this task. I also one hot encoded most of the categorical features, and undertook some specific transformations for a few other features.

# Result
I achieved a score of 0.7185 (AUC). This model was ranked 5th among 71 participants.
