# Document-Matching-and-Keyword-Analysis-System-_
# Project Overview
This project is designed to compare multiple documents against a "master" document to determine the percentage match between them. It also extracts and analyzes keywords from the documents to help identify commonly repeated terms. This system can be useful in document verification, plagiarism detection, or analyzing textual similarities.

# Key Features
* PDF Document Reading: Reads and processes PDF documents to extract text.
* Text Similarity Calculation: Uses the difflib library to calculate a percentage match between the master document and other documents.
* Keyword Extraction: Extracts keywords from each document by tokenizing the text and removing common stopwords.
* Results Table: Displays the match percentage and extracted keywords for each document in a neatly formatted table.
* Highly Repeated Keywords: Identifies and saves highly repeated keywords across all documents.
* Visualization: Plots a bar chart showing the match percentage for each document compared to the master document.
