# Applied-Data-Science-24
Course materials for PHYS247-Introduction to Applied Data Science (University of California, Riverside)

## Session 1: Python Installation & Basics
We introduced Python programming and how to get started using Anaconda, VSCode, and Google Colab. Topics covered include variables, data types, basic math operations, and string manipulations.

📌 **Resources**:
- [Anaconda](https://docs.anaconda.com/free/anaconda/index.html)
- [VSCode](https://code.visualstudio.com/)
- [Google Colab](https://colab.research.google.com/)
- [Python Crash Course (~10 min)](https://www.youtube.com/watch?v=fWjsdhR3z3c)
- [Full Python Course (~6 hrs)](https://www.youtube.com/watch?v=_uQrJ0TkZlc)

## Session 2: Data Structures & Control Flow
We explored essential Python data structures including lists, tuples, sets, and dictionaries. Control flow mechanisms such as `if`, `else`, `for`, and `while` loops were introduced for basic decision-making and iteration.

📌 **Topics**:
- Mutable vs immutable types
- Indexing & slicing
- Loops & conditional statements
- `break` / `continue`

## Session 3: Functions & Numpy
This session covered user-defined functions, scope, return values, and basic error handling. We also introduced NumPy for efficient numerical computation, including arrays, array operations, and broadcasting.

📌 **Topics**:
- Function definition, arguments, return values
- Built-in vs custom functions
- NumPy arrays & operations
- Vectorized math with NumPy

## Session 4: Introduction to Bayesian Statistics

We introduced the **Bayesian framework**, where probability represents a degree of belief. Updated beliefs are computed after observing data using **Bayes’ Theorem**:

**P(hypothesis | data) = [P(data | hypothesis) * P(hypothesis)] / P(data)**

- **Prior**: P(hypothesis) – belief before seeing data  
- **Likelihood**: P(data | hypothesis) – how well data fits the hypothesis  
- **Posterior**: P(hypothesis | data) – updated belief after seeing data

We discussed how Bayesian thinking aligns with human reasoning and demonstrated how changing priors affects posteriors. Students also completed an assignment applying Bayesian reasoning in practice.

📌 **Topics**:
- Bayes' Rule and conditional probabilities
- Prior, likelihood, and posterior interpretation
- Real-world applications of Bayesian inference
- Hands-on homework to reinforce concepts

## Session 5: Naive Bayes & Spam Filtering

We applied **Bayesian reasoning** to build a Naive Bayes classifier for text classification. Using a labeled dataset of SMS messages, we predicted whether a message is *spam* or *ham* based on word frequency.

Naive Bayes assumes conditional independence among features. Given a message with a "bag of words," the spam probability is computed as:

**P(Spam | w1, w2, ..., wn) ∝ P(Spam) * P(w1 | Spam) * P(w2 | Spam) * ... * P(wn | Spam)**

We applied **Laplace smoothing** to avoid zero probabilities for unseen words, and handled out-of-vocabulary words by removing them from the input. A demonstration classified a message as spam with ~70% probability based on its word content.

📌 **Topics**:
- Naive Bayes formula & assumptions
- SMS dataset preprocessing with NLTK
- Stop word filtering & stemming
- Likelihood computation & model evaluation

## Session 6 & 7: NLP & Naive Bayes with Real Data

In these sessions, we extended the Naive Bayes spam classifier to a real-world dataset of ~4,000 SMS messages using Natural Language Processing (NLP). We explored the entire preprocessing pipeline:

- **Stop word removal** to exclude uninformative common words  
- **Stemming** to reduce words to their root forms  
- **Punctuation removal** to clean the dataset  
- **Encoding** categorical labels (spam/ham) as numeric values for model training

We discussed Laplace smoothing to avoid zero-frequency problems, and used **NLTK** for most preprocessing steps. A hands-on walkthrough was done to compute the spam probability of a new message using learned word distributions.

📌 **Topics**:
- NLP basics: stop words, stemming, bag-of-words
- Data cleaning for text classification
- SMS dataset preprocessing with NLTK
- Applying Naive Bayes to real data and interpreting results

## Session 8: Markov Chain Monte Carlo (MCMC)

In this session, we introduced **Markov Chain Monte Carlo (MCMC)** methods, used for sampling from complex probability distributions, particularly posteriors in high-dimensional Bayesian inference problems.

We demonstrated a Markov Chain using a weather model (Sunny/Rainy), where the state of each day depends only on the previous day. Given a transition matrix and an initial condition, we computed the long-term probability of each state using **matrix multiplication** and eigenvectors.

Key takeaways included the idea that MCMC allows probabilistic exploration of a space where direct computation is intractable.

📌 **Topics**:
- Basics of MCMC sampling
- Markov property and state transitions
- Transition matrix and long-term equilibrium
- Link between linear algebra and probability

## Session 9: Support Vector Machines (SVM)

We introduced **Support Vector Machines (SVM)** as a supervised learning algorithm for binary classification. SVMs aim to find the **optimal separating hyperplane** that maximizes the margin between two classes in a dataset.

Given labeled data points x_i with labels y_i ∈ {-1, +1}, the distance from a point to the decision boundary is defined by the projection onto the normal vector w:

**D = w · x + b**

Points on one side of the margin are classified as +1 and on the other as -1. We discussed the optimization problem behind SVMs and how maximizing the margin leads to better generalization.

📌 **Topics**:
- Linear classification with maximum margin
- Decision boundaries and support vectors
- Optimization of SVM objective
- Conceptual foundation for kernel methods