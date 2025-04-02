# 📊 Introduction to Applied Data Science – PHYS247

Welcome to the official GitHub repository for **PHYS247 – Introduction to Applied Data Science** at the **University of California, Riverside**. This course is designed to introduce core concepts in Python programming, statistics, machine learning, and data-driven modeling through hands-on examples.

👨‍🏫 **Instructor:** Prof. Bahram Mobasher  
🧑‍💻 **Teaching Assistant:** [Sina Taamoli](https://sinataamoli.github.io/)  
📬 **Contact:** sina.taamoli@email.ucr.edu

---

## 📦 Tools & Libraries Used

We used a variety of open-source tools throughout the course:

- Python 3 (via Anaconda)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [NLTK](https://www.nltk.org/)
- [scikit-learn](https://scikit-learn.org/)
- [Google Colab](https://colab.research.google.com/)

---

## 📘 Course Outline

Each session builds on the previous one, starting from the fundamentals of Python programming and progressing into data science, machine learning, and probabilistic inference.

---

## 🔧 Session 1: Python Installation & Basics

We began with installing Anaconda, VSCode, and Google Colab. This session covered:

- Basic syntax and math operations
- Variables, strings, and types
- Introduction to Python scripting

📌 **Resources**:
- [Anaconda](https://docs.anaconda.com/free/anaconda/index.html)
- [VSCode](https://code.visualstudio.com/)
- [Google Colab](https://colab.research.google.com/)
- [Python Crash Course (~10 min)](https://www.youtube.com/watch?v=fWjsdhR3z3c)
- [Python Full Course (~6 hrs)](https://www.youtube.com/watch?v=_uQrJ0TkZlc)

---

## 🔁 Session 2: Data Structures & Control Flow

We explored essential Python structures:

- Lists, tuples, dictionaries, sets
- Indexing, slicing, and looping (`for`, `while`)
- Conditional logic and `if-else` flow

---

## 🧮 Session 3: Functions & NumPy

Building reusable code with functions and diving into vectorized operations using NumPy:

- Writing functions with parameters and return values
- Understanding variable scope
- Introduction to arrays, broadcasting, and efficient math

---

## 📊 Session 4: Introduction to Bayesian Statistics

Bayesian thinking was introduced through:

> **P(hypothesis | data) = [P(data | hypothesis) * P(hypothesis)] / P(data)**

We covered:
- Prior, likelihood, posterior
- Conditional probability and belief updates
- Real-world reasoning with Bayesian logic

---

## ✉️ Session 5: Naive Bayes & Spam Filtering

We implemented a **Naive Bayes classifier** on a labeled SMS dataset.

- Text preprocessing and tokenization
- Word probability calculations
- Classification using bag-of-words & Laplace smoothing

📌 Tools used: `NLTK`, `collections.Counter`

---

## 🧠 Session 6 & 7: NLP & Naive Bayes on Real Data

We scaled up our model to a 4,000+ message dataset:

- Natural Language Processing pipeline:  
  stop word removal, stemming, and punctuation filtering
- Label encoding & feature extraction
- Spam probability modeling using real-world messages

📌 Tools used: `nltk`, `pandas`, `scikit-learn`

---

## 🎲 Session 8: Markov Chain Monte Carlo (MCMC)

We modeled probabilistic processes like weather prediction using **Markov Chains**.

- Transition matrices & state probabilities  
- Eigenvector convergence for steady states  
- Motivation for using MCMC in high-dimensional Bayesian models

📌 Concepts bridged with linear algebra

🧠 Fun fact: This lays the groundwork for deep generative models and probabilistic simulations.

---

## 🧭 Session 9: Support Vector Machines (SVM)

We explored the SVM algorithm for binary classification.

- Finding the optimal separating hyperplane
- Maximizing the margin between data classes
- Decision function: **D = w · x + b**

📌 Topics:
- Support vectors and geometric intuition
- Linear classifiers
- Optimization-based learning

---

## 🌐 More Resources

- [Python for Data Science Handbook (Jake VanderPlas)](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [StatQuest (YouTube)](https://www.youtube.com/user/joshstarmer)

---

## 🏁 Summary

This course blends theoretical foundations with practical coding to develop the mindset and skillset of a data scientist. Whether it’s classification, inference, or modeling uncertainty — you’ll find the tools introduced here highly transferable to real-world applications.

---

![data science banner](https://cdn.analyticsvidhya.com/wp-content/uploads/2015/09/Data-Science-Life-Cycle.png)