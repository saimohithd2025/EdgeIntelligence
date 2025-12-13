**Gender Classification using Naive Bayes**

This project utilises a Naive Bayes classifier to classify names according to gender (male/female).  The algorithm uses probabilistic reasoning to estimate the gender of unseen names after learning patterns from a labelled dataset of names.
The project is straightforward, lightweight, and appropriate for learning the principles of probability-based models, feature extraction from text input, and machine learning categorisation.

**Data**

There are 7,994 names in the collection.
Every name falls into one of two categories:

 1. Male
 2. Female

The model uses this dataset as its raw training data to identify patterns.To assess performance on unseen names, the data is divided into training and testing sets.

**Task**

This binary classification issue is frequently seen in jobs involving text-based machine learning and natural language processing (NLP).

**Model**

1. The Naive Bayes Classifier method is utilised.
2. It is a Bayes Theorem-based probabilistic machine learning model.
3. The model determines whether a given name is likely to be male or female.
4.The gender with the highest posterior probability is chosen for classification.

**Learning Process**

The model picks certain statistical trends during training, including:
1. Female names are more likely to end in "a" or "e."
2. Male names are more likely to end in "n" or "d."
The design:
  a.counts how often a characteristic appears in each class.
  b.Conditional probabilities are calculated
  c.uses the training data to automatically modify probability

**Accuracy and Evaluation**

1.The model achieves an accuracy of approximately 77 %.

2. Accuracy is evaluated using unknowm test data, ensuring fair performance.

3. This indicates that the model generalizes reasonably well to new names.

**Loss Function**

1.No explicit loss function is used.


2. Naive Bayes relies on probability estimation rather than optimization-based loss minimization.
