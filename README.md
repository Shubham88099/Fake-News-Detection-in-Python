# Fake-News-Detection-in-Python
This project aims to detect fake news using Python and machine learning. The model analyzes the textual content of online articles to classify them as FAKE or REAL based on linguistic and statistical patterns.

# Project Workflow

1. Data Loading & Cleaning
   
 * Load the CSV file, check for missing/null values, and clean the text (removing punctuation, stopwords, and converting to lowercase).
2. Exploratory Data Analysis (EDA)

* Visualize data distribution between FAKE and REAL labels.

 * Analyze word frequency using WordCloud or CountVectorizer.

3. Text Preprocessing

 * Tokenization and lemmatization
 * Stopword removal
 * Vectorization using TF-IDF

4. Model Training
 * Trained several classifiers, including:

* Logistic Regression

* Naive Bayes

* Support Vector Machine (SVM)

* Random Forest

5.Model Evaluation
 * Measured model performance using:
 * Accuracy

 * Precision
* Recall
 * F1-Score

 * Confusion Matrix

  #  Libraries Used

 * pandas
 * numpy
 * matplotlib
 * seaborn
 * scikit-learn
 * nltk
 * wordcloud

 # Results

  * Achieved ~95% accuracy with Logistic Regression and TfidfVectorizer.

  * The model effectively distinguishes between real and fake news based on text content.
