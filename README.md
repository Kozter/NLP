# Natural Language Processing
### Text processing, feature extraction and representation by using both TF and TF-IDF schemes
Given a data file (NLP.csv), where reviews on movies are provided.

1. Data preparation: load the file, access the columns, then through printing and visualization,
understand the meaning in each column. Then create a new column, name it as ‘description’ by
concatenating the strings from two columns: tagline and overview.

2. Text processing: convert words in ‘description’ to lower case, remove white space, remove
words from stop_words (from nltk package), remove special characters (such as ‘/n’) and add other
necessary processings.

3. TF and TF-IDF representation on ‘description’: for each sample in the dataset, generate TF
and TF-IDF representation for each sample based on the column of ‘description’.

### Topic modelling
Use TF and TF-IDF representation generated in task 2.1 to perform topic modelling. Select
and compare two topic modelling algorithms from LDiA, Truncated SVD, Word2Vec or any other
topic modelling algorithms, and then analyze the results.

### Analysis Task: Searching for similar movies
Assume you would like to find similar movies as ‘Spider-Man’ based on the given dataset,
what would you do? Please introduce your solution step-by-step, where such information should be
provided:
1. Details on each step and expected inputs/outputs of each step
2. Major algorithm to be used to solve this problem
3. The results
4. Analysis on the results
Be noted visualization should be used when exploring the data or illustrating the results.
