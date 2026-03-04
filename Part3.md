# Part 3: Advanced Model
**[End of Week 11]**

---

Create the best Fake News predictor that you can come up with. This should be a more complex model than the simple logistic regression model you created in Part 2, either in the sense that it uses a more advanced method, or because it uses a more elaborate set of features.

For example, you might consider using:
- A **Support Vector Machine**
- A **Naive Bayes Classifier**
- A **neural network**

The input features might use more complex text representations, such as **TF-IDF weights** or **continuous word embeddings**.

Report necessary details about your models ensuring full reproducibility. This could include, for example, the choice of relevant parameters and how you chose them. Make sure to argue for why you chose this approach over potential alternatives.

---

## Optional: Training on the Full FakeNewsCorpus

If you want to go even further, you might want to try training your models on even more data. The full [FakeNewsCorpus](https://github.com/several27/FakeNewsCorpus/releases/tag/v1.0) is a total of **9GB** of source material available for training your model.

You will need to use a multi-part decompression tool, e.g. `7z`. Given all the files, execute the following command:
```bash
7z x news.csv.zip
```

This should create a **27GB** file on disk (29,322,513,705 bytes). You may find it challenging to run your data processing pipeline on the entire FakeNewsCorpus, so take care if you attempt this step.