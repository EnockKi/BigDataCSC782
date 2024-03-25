# Big Data - CSC 782 Fall 2023 EKU - Final Project- Textual Analysis of the EKU Student Handbook 2022 using Word Count, Term Frequency - Inverse Document Frequency and Latent Dirichlet Allocation.

## Components of the project
__________________________________
### Word Count using MapReduce in Hadoop:
Implemented a word count algorithm using framework in Hadoop using Manjaro Linux environment.
Preprocessed the text file by extracting the text from the PDF format.
The text data was cleaned by removing the common words.
The MapReduce function involved mapping each word to a key-value pair and then reducing the pair to count the occurrences of each word. Run the project through HDFS (Hadoop Distributed File System)
### TF-IDF MapReduce Framework and Preprocessing: 
Evaluated the importance of terms within a document relative to a collection of documents
Preprocessing steps involved tokenization, removal of stops and stemming.
Mapped terms to their respective documents and combining the final TF-IDF score.
Bash pipeline was utilized to automate the processes
### Latent Dirichlet Allocation (LDA) Implementation:
Topic modeling is not effective when implemented directly in MapReduce framework for Hadoop due iterative nature, but it still possible to adapt LDA for distributed computing environments.

