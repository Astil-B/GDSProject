# Part 1: Data Processing
**[End of Week 8]**

---

In the first part of the project, you should work on retrieving, structuring, and cleaning data. You will be using a subset of the FakeNewsCorpus dataset in your project, which is available from Absalon. You can also find [more information about the full dataset](https://github.com/several27/FakeNewsCorpus) including how the data is collected and the available fields.

---

## Task 1

Retrieve a sample of the FakeNewsCorpus from [`news_sample.csv`](https://raw.githubusercontent.com/several27/FakeNewsCorpus/master/news_sample.csv) and structure, process, and clean it. You should follow the methodology you developed in Exercise 1. When you have finished cleaning, process the text using [NLTK](https://www.nltk.org/), which has built-in support for many common operations. Try the following:

- **Tokenize** the text.
- **Remove stopwords** and compute the size of the vocabulary. Compute the reduction rate of the vocabulary size after removing stopwords.
- **Remove word variations with stemming** and compute the size of the vocabulary. Compute the reduction rate of the vocabulary size after stemming.

Describe which procedures (and which libraries) you used and why they are appropriate.

## Task 2

Apply your data preprocessing pipeline to the 995,000 rows sampled from the FakeNewsCorpus: **995K FakeNewsCorpus subset** (available for download on Absalon).

## Task 3

Explore your processed version of the 995K dataset and make at least **three non-trivial observations or discoveries** about the data. These observations could relate to outliers, artefacts, or genuinely interesting patterns that could potentially be used for fake-news detection.

Address the following questions in your exploration:

1. Describe how you ended up representing the FakeNewsCorpus dataset (e.g. as a Pandas DataFrame). Argue for why you chose this design.
2. Did you discover any inherent problems with the data while working with it?
3. Report key properties of the dataset through statistics or visualization.

The exploration can include, but need not be limited to:

1. Counting the number of URLs in the content.
2. Counting the number of dates in the content.
3. Counting the number of numeric values in the content.
4. Determining the 100 most frequent words appearing in the content.
5. Plotting the frequency of the 10,000 most frequent words — are there any interesting patterns?
6. Running the analysis from points 4 and 5 both before and after removing stopwords and applying stemming — do you see any difference?

> **Note:** Simple observations such as counting missing values or plotting the distribution over domains are a good starting point, but aim to go beyond these with more creative or insightful findings.

## Task 4

Split the resulting dataset into **training**, **validation**, and **test** splits. A common strategy is to split the data uniformly at random in an **80% / 10% / 10%** ratio:

- **Training data** — used to train your baseline and advanced models.
- **Validation data** — used for model selection and hyperparameter tuning.
- **Test data** — should only be used in Part 4.