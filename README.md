# Bag-Of-Words-using-NLP
Overview
The code performs the following tasks:

Text Cleaning: Removes non-alphabetic characters, converts to lowercase, tokenizes, and stems the text.

Tokenization and Lemmatization: Splits the text into sentences and lemmatizes them.

Stopword Removal: Eliminates common English stopwords to improve model accuracy.

Bag of Words Model: Utilizes scikit-learn's CountVectorizer to create a Bag of Words model with a maximum of 1500 features.

Usage

Install Python and required dependencies (pip install -r requirements.txt).

Run text_preprocessing.py to preprocess text and generate the model.

Dependencies

Python 3.x

NLTK

scikit-learn

File Structure

text_preprocessing.py: Contains preprocessing and model creation code.

requirements.txt: Lists necessary dependencies.
