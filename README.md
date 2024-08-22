# MOVIE REVIEWS SENTIMENT ANALYZER.
A Machine Learning model that analyzes movie reviews and categorizes them as either, **POSITIVE** or **NEGATIVE**.

## Why Did I Create This Project?
This is a capstone project I've done during my Data Science and Machine Learning journey in order to test my Data Science and Machine Learning skills.

## Which Technologies Did I User During Development?
1. Python Programming Language
2. Jupyter Notebook
3. Excel
4. NLTK
5. Sci-kit Learn
6. Git


## What Did I Learn During Development of the Project?
1. Since the dataset used was unorganised - each review was stored in its individual TXT file, so, I had to develop a [Python script](https://github.com/joelakwam/data-processing-script) that loops through the directory containing the TXT files and saves each review in one newly created CSV file.
2. Data Wrangling using Python - parsing the corpus to make it suitable for training by removing, **WHITESPACES, PUNCTUATION MARKS, INTEGERS, HTML tags** and transforming the corpus to **LOWERCASE**.
3. Utilizing the **NLTK Library** for parsing the corpus by removing **STOPWORDS, TOKENIZING** and **STEMMING**.


## Results.
- I trained the model using various Machine Learning algorithms and below were the results with their respective accuracy:-
1. Logistic Regression (90%)
2. Decision Tree Classifier (72%)
3. Random Forest Classifier (86%)
4. Naive Bayes (87%)
