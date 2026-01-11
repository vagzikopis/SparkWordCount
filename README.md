### PySpark Big Data Assignments
This repository contains two data analysis tasks using Apache Spark and pyspark. The projects demonstrate the use of the RDD API for unstructured text and the DataFrame API for structured CSV data.

#### Task 1: Word Length Analysis (RDD API)
Calculates the average word length for words starting with each letter (a-z) in Sherlock Holmes text file.
Process:
   * Cleaned text (lowercase, punctuation removal).
   * Filtered out words starting with numbers.
   * Used MapReduce logic to aggregate total lengths and counts.


#### Task 2: Airline Twitter Sentiment (DataFrame API)
Analyzes Twitter data to identify top keywords per sentiment and primary complaint reasons per airline.

Process:
   * Regex-based punctuation removal and lowercase conversion.
   * Utilized StopWordsRemover and custom filters to exclude stop words, airline names, handles (e.g., "jetblueair"), and short noise.
   * Used Window Functions to rank the top 5 words per sentiment and the #1 complaint reason for each airline.
