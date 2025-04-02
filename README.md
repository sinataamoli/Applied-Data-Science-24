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

We introduced the **Bayesian framework**, where probability represents a degree of belief, and updated beliefs are computed after observing data using **Bayes' Theorem**:

\[
P(\text{hypothesis} \mid \text{data}) = \frac{P(\text{data} \mid \text{hypothesis}) \cdot P(\text{hypothesis})}{P(\text{data})}
\]

- **Prior** \( P(\text{hypothesis}) \): Initial belief before observing data  
- **Likelihood** \( P(\text{data} \mid \text{hypothesis}) \): How likely the data is under a hypothesis  
- **Posterior** \( P(\text{hypothesis} \mid \text{data}) \): Updated belief after seeing data

We discussed how Bayesian thinking aligns with human reasoning and demonstrated how changing priors affects posteriors. Students also completed an assignment applying Bayesian reasoning in practice.

📌 **Topics**:
- Bayes' Rule and conditional probabilities
- Prior, likelihood, and posterior interpretation
- Real-world applications of Bayesian inference
- Hands-on homework to reinforce concepts

## Session 5: Naive Bayes & Spam Filtering

We applied **Bayesian reasoning** to build a Naive Bayes classifier for text classification. Using a labeled dataset of SMS messages, we predicted whether a message is *spam* or *ham* based on word frequency.

Naive Bayes assumes conditional independence among features. Given a message with a "bag of words," the spam probability is computed using:

\[
P(\text{Spam} \mid w_1, w_2, ..., w_n) \propto P(\text{Spam}) \cdot \prod_{i=1}^n P(w_i \mid \text{Spam})
\]

We applied **Laplace smoothing** to avoid zero probabilities for unseen words, and handled out-of-vocabulary words by removing them from the input. The example demonstrated a classification based on the words “write” and “password,” showing ~70% spam probability.

📌 **Topics**:
- Naive Bayes formula & assumptions
- SMS dataset preprocessing with NLTK
- Stop word filtering & stemming
- Likelihood computation & model evaluation