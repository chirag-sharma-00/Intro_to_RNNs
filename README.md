# COMPSCI 189 Project T - Introduction to RNNs (Team Chairun) 
This repository contains materials for COMPSCI 189 Project T, Week 10. We aim to provide students with a thorough introduction to RNNs, and specifically, GRUs and how they are being applied to modern portfolio theory

# Learning Goals: 
1) **Goal:** Gain an understanding of how the RNN improves upon feed-forward networks, the vanishing gradient problem, and how the GRU solves this issue. <br>
   **Method:** The note and slideshow offer an introduction to RNN and what flaws in conventional NNs they were designed to fix. The assignments reinforce this by first having students explore the workings of a simple RNN under the hood, and then introducing a toy example designed specifically to highlight potential use-cases for RNNs (and LSTMs). The quiz questions and teaching materials also discuss the vanishing gradient problem, and how LSTMs and GRUs were designed to fix this problem. While the notebook doesn't specifically address the vanishing gradient issue with an example, it definitely offers a lot of room to play around with these more advanced neural networks. 
   
2) **Goal:** A brief overview of data manipulation and processing for NLP tasks <br>
   **Method:** The focus of this project is understanding and implementing RNNs, however, we also give students a chance to manipulate data for an NLP task, from data sources that are typically used in the finance industry (like yahoo finance). We also have an embeddings.ipynb notebook that uses the industry-standard package gensim to build a Word2Vec model for news data - this acts as a great segue to other topics in NLP. 

3) **Goal:** Learn how to use the Keras functional API to build Bidirectional GRU networks <br>
   **Method:** All of our models are built using TensorFlow and Keras, using several features of the API such as Sequential Models, Bidirectional Wrappers, etc. We hope that by the end of the assignment, students are comfortable coding up neural networks in keras and understand exactly the sort of matrix manipulations required to use the API.
   
4) **Goal:** An overall appreciation of how NLP and ML can be used in fields like portfolio optimization <br>
   **Method:** The main part of the project, as mentioned earlier, is built to try and tackle one of finance's most longstanding problems - stock price prediction/classification. While we don't expect the students to get exceptionally high accuracy scores, we hope that the creativity of the approach, i.e. combining word embeddings and stock price movement to generate vector representations of stocks, inspires students to think of novel ways to use NLP and neural networks in seemingly unrelated fields.

# Navigating the Repo: 
Our repo contains three main sections: teaching, assignments, and quiz.

- **Teaching:** contains both a note and slideshow which can be used as teaching materials for this project.
- **Assignments:** contains 3 notebooks for 3 separate assignments:
  - `RNN_from_scratch Assignment.ipynb` contains an assignment for implementing an RNN model from scratch, without using any machine learning packages.
  - `Warm-Up Assignment.ipynb` contains a warm-up exercise for implementing RNNs in Keras and applying them to a sequence classification task.
  - `Main Project.ipynb` is the main project notebook for the price movement classifier exercise that was described earlier and is explained in detail in the note.
- **Solutions:** contains the solution notebooks for the 3 assignments above.
- **Embeddings Generation:**: contains notebook and data used to generate the `embeddings.csv` file that is used in the project.
- **Quiz:** contains a brief quiz which can be used to test a student's understanding of the topics covered.
