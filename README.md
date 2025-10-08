# Mini-Google-Search
A project implementing using data structures and algorithms for efficient computation.
🧠 Mini Google Search Engine

🔍 A Text-based Search and Ranking System using Python

📘 Overview
The Mini Google Search Engine is a small-scale information retrieval project that replicates the fundamental working principles of Google’s search mechanism. Built using Python, it efficiently searches through a collection of local text files, processes them, and ranks the most relevant results based on cosine similarity between the user query and document vectors.
The goal of this project is to understand how search engines index, retrieve, and rank textual data using simple yet powerful algorithms.


🎯 Objectives
Develop a small-scale search engine using Python.
Learn and apply text preprocessing, inverted indexing, and document ranking.
Implement cosine similarity to measure relevance between queries and files.
Build an interactive Gradio web interface for users to perform searches easily.
⚙️ System Architecture
Text Files → Preprocessing → Inverted Index → Vectorization → Similarity Computation → Ranked Output


🧩 Components
Input Layer: A collection of .txt files (Wikipedia articles).
Preprocessing Module: Cleans text by removing punctuation, numbers, and stopwords.
Inverted Index Module: Builds a dictionary mapping words to the files they appear in.
Vectorization Module: Represents each document as a word-frequency vector.
Similarity Module: Calculates cosine similarity between query and documents.
Interface Layer: Displays ranked results in a web UI using Gradio.


🛠️ Technologies Used
Tool	Purpose
Python	Programming language
Google Colab	Development environment
Gradio	Interactive web interface
Libraries: os, re, collections, math	File handling, preprocessing, indexing
Dataset	Wikipedia text files


🧮 Workflow
Load Files: Import text files from the dataset folder.
Preprocess: Convert to lowercase, remove punctuation and stopwords.
Build Inverted Index: Map words to corresponding documents.
Create Vectors: Convert documents into frequency vectors.
Rank Documents: Use cosine similarity to find the most relevant files.
Display Results: Output is shown neatly in a Gradio interface.


🌟 Key Features
🔹 Single-Word Search: Finds documents containing the query word.
🔹 Multi-Word Search (AND/OR): Supports complex keyword queries.
🔹 “Did You Mean?” Suggestions: Uses Levenshtein distance for typo correction.
🔹 File Recommendation System: Suggests similar documents.
🔹 File Vector Display: Shows most frequent words per document.
🖥️ User Interface


The Gradio interface provides an easy-to-use web application with four tabs:

Single Word Search
Multi-word Search (AND / OR)
File Recommendation
File Vector Display
Each tab allows the user to perform different types of searches and view results interactively.


📊 Results and Observations
Successfully retrieves relevant documents for both single and multi-word queries.
Efficiently ranks documents using cosine similarity.
The Gradio interface makes the system interactive and beginner-friendly.
Demonstrates real-world information retrieval principles on a small dataset.


🧾 Example Output
Query: “Virat”
Output: Returns cricket-related text files with similarity scores displayed in descending order.
Query: “machine learning”
Output: Returns files related to technology and AI topics.


🚀 Future Enhancements
Implement TF-IDF weighting for improved ranking accuracy.
Add phrase-based search for exact match retrieval.
Deploy as a web application using Flask or Streamlit.
Extend dataset for large-scale document retrieval.

📚 References
Stanford CS276 Lecture Notes – Vector Space Models
Medium: Using Inverted Index for Efficient Document Similarity
Introduction to Information Retrieval – Manning, Raghavan, Schütze

🏁 Conclusion
The Mini Google Search Engine successfully replicates the basic principles of how real-world search engines operate—from text preprocessing and indexing to ranking and user interaction. It is an ideal academic project for understanding information retrieval systems and the mathematics behind search algorithms.


