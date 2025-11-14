Machine Learning - Home Assignment 4 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Course: CS5710 Machine Learning

Institution: University of Central Missouri

Student Name: Nikhilesh Katakam

Student ID: 700772365

Semester: Fall 2025

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📌Overview
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This repository contains my submission for Home Assignment 4, which includes:

Part A: Manual clustering calculations (Hierarchical Clustering + K-Means)

Part B: Short-answer questions on clustering and NLP concepts

Part C: Python code for tokenization, lemmatization, POS filtering, Named Entity Recognition (NER), and pronoun ambiguity detection.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📍Part A: Clustering Calculations
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q1: Hierarchical Clustering (Single-link & Average-link)

   . Built the full Euclidean distance matrix for all points.

   . Applied Single-Link (MIN) and Average-Link hierarchical clustering.

   . Recorded merge steps and dendrogram structures.

Q2: K-Means Clustering (K = 3)

   . Calculated distances from each point to initial centroids.

   . Assigned points to nearest clusters (tie → assign to smallest index centroid).

   . Computed new centroids after each iteration.

   . Continued iterations until cluster membership stabilized (convergence).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📍Part B: Short Answer Concepts
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Topics explained include:

  . Agglomerative vs. Divisive hierarchical clustering
  
  . Inter-cluster vs. intra-cluster distance in cluster quality
  
  . Linkage methods: Single, Complete, Average
  
  . Tokenization role in NLP
  
  . Stemming vs. Lemmatization
  
  . Word sense and pronoun ambiguity
  
  . Why POS tagging cannot predict words independently
  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📍Part C: Python Code
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| File | Description |
| :--- | :--- |
| `q1_nlp.py` | Tokenization → Stopword removal → Lemmatization → Keep only nouns & verbs |
| `q2_ner_pronoun_warning.py` | Performs Named Entity Recognition and checks for pronoun ambiguity |

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📍Requirements
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

    pip install spacy
    python -m spacy download en_core_web_sm
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📍Usage 

Run:

    python q1_nlp.py
    python q2_ner_pronoun_warning.py
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

END 



    
