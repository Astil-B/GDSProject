# Part 2: Simple Logistic Regression Model
**[End of Week 10]**

---

You should create and train a baseline model for your Fake News predictor that performs binary classification to predict whether an article is reliable or fake.

---

## Task 1

Briefly discuss how you grouped the labels into two groups. Are there any limitations that could arise from the decisions you made when grouping the labels?

## Task 2

Start by implementing and training a simple logistic regression classifier using a fixed vocabulary of the **10,000 most frequent words** extracted from the `content` field, as the input features. You do not need to apply TF-IDF weighting to the features.

It should take no more than five minutes to fit this model on a modern laptop, and, as guidance, it should be possible to achieve an F1 score of ~94% on your test split. However, this F1 score is based on certain assumptions about how you have split your data and will not apply to every group. Do not worry too much if the F1 score with your logistic regression model is substantially below 94%.

Write in your report the performance that you achieve with your implementation of this model, and remember to report any hyper-parameters used for the training process.

## Task 3

Consider whether it would make sense to include meta-data features as well. If so, which ones, and why? If relevant, report the performance when including these additional features and compare it to the first baselines. Discuss whether these results match your expectations.

---

> **Note:** For the remainder of the project, we will limit ourselves to main-text data only (i.e. no meta-data). This makes it easier to do the cross-domain experiment in Part 4, which does not have the same set of meta-data fields.