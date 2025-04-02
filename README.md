# Introduction to Applied Data Science – PHYS247

This repository contains materials for **PHYS247: Introduction to Applied Data Science**, a course offered at the University of California, Riverside. It aims to introduce students to core tools, techniques, and ways of thinking in modern data science using Python.

**Instructor**: Prof. Bahram Mobasher  
**Teaching Assistant**: [Sina Taamoli](https://sinataamoli.github.io/)  
**Contact**: sina.taamoli@email.ucr.edu

---

## Tools and Libraries

The course utilized a wide array of industry-standard open-source packages:

- **Python 3 (Anaconda)**
- [NumPy](https://numpy.org/) – numerical computing
- [Pandas](https://pandas.pydata.org/) – data structures and analysis
- [Matplotlib](https://matplotlib.org/) – data visualization
- [NLTK](https://www.nltk.org/) – text processing
- [scikit-learn](https://scikit-learn.org/) – machine learning
- [Google Colab](https://colab.research.google.com/) – cloud-based notebook execution

---

## Course Overview

The course begins with programming fundamentals and gradually incorporates statistical inference, probabilistic modeling, and machine learning techniques. By the end, students will be able to apply data science principles to real-world problems.

---

## Session 1: Python Installation & Basics

We introduced Python programming and walked through setting up development environments via Anaconda, VSCode, and Google Colab. Students learned about:

- Basic syntax and interactive scripting
- Data types and expressions
- Simple mathematical operations and variables

**Resources**:
- [Anaconda](https://docs.anaconda.com/free/anaconda/index.html)
- [VSCode](https://code.visualstudio.com/)
- [Google Colab](https://colab.research.google.com/)
- [Python Crash Course (~10 min)](https://www.youtube.com/watch?v=fWjsdhR3z3c)
- [Python Full Course (~6 hrs)](https://www.youtube.com/watch?v=_uQrJ0TkZlc)

---

## Session 2: Data Structures & Control Flow

This session covered foundational programming constructs necessary for data processing:

- Lists, tuples, dictionaries, and sets
- Slicing, indexing, and nested data structures
- Conditional statements (`if`, `else`) and looping (`for`, `while`)
- Use of control keywords like `break` and `continue`

Applications: These skills are critical for parsing and processing structured datasets and implementing custom algorithms.

---

## Session 3: Functions and NumPy

We introduced the concept of modular code through user-defined functions and then transitioned into efficient numerical computing with NumPy.

- Function definitions, return values, and scope
- Built-in vs. user-defined functions
- Vectorization, broadcasting, and array operations using NumPy

Applications: Enables high-performance computation for scientific simulations, data manipulation, and model evaluation.

---

## Session 4: Bayesian Statistics

Bayesian inference was introduced as a method for updating probabilities based on observed data. Using Bayes' Theorem:

**P(hypothesis | data) = [P(data | hypothesis) * P(hypothesis)] / P(data)**

Topics:
- Prior, likelihood, and posterior probability
- Subjective vs. frequentist interpretations of probability
- Real-world reasoning under uncertainty

Applications: Used in spam filtering, diagnostics, risk analysis, and recommendation systems.

---

## Session 5: Naive Bayes & Text Classification

We implemented a Naive Bayes classifier to detect spam messages using a bag-of-words approach.

- Calculating word-level probabilities
- Laplace smoothing to avoid zero-probability issues
- Evaluation using predictive posterior probabilities

Applications: Widely used in spam detection, sentiment analysis, and document classification.

---

## Session 6 & 7: Natural Language Processing (NLP) with Real Data

Using a dataset of 4,000+ SMS messages, we built a complete spam classifier with text preprocessing and machine learning:

- Tokenization, stop word removal, and stemming
- Data cleaning and transformation
- Encoding labels and generating feature vectors

Applications: Foundations of text-based AI systems including search engines, recommendation engines, and chatbots.

---

## Session 8: Markov Chain Monte Carlo (MCMC)

We introduced MCMC, a class of algorithms for sampling from complex probability distributions when direct computation is intractable.

- Markov Chains and state transitions
- Transition matrices and steady-state probabilities
- Relevance of eigenvectors in convergence

Applications: Used in physics, Bayesian computation, natural language generation, and probabilistic inference in large-scale systems.

---

## Session 9: Support Vector Machines (SVM)

We concluded the course with Support Vector Machines, a supervised learning algorithm for binary classification.

- Hyperplane separation and decision boundaries
- Maximizing margin between classes
- Role of support vectors in optimization

Applications: Used in image recognition, gene classification, handwriting detection, and bioinformatics.

---

## Supplementary Learning Materials

- [Python for Data Science Handbook – Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [StatQuest by Josh Starmer (YouTube)](https://www.youtube.com/user/joshstarmer)
- [The Elements of Statistical Learning (Free Book)](https://web.stanford.edu/~hastie/ElemStatLearn/)

---

## Final Remarks

This course provides a comprehensive and applied introduction to data science. It emphasizes both the programming foundations and the statistical thinking required to analyze data, build models, and draw insights in a reproducible way.

Students are encouraged to build on these foundations with deeper explorations into machine learning, data visualization, and domain-specific analytics.