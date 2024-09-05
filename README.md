# Movie Reviews Preprocessing with NLTK and SpaCy
This project demonstrates the use of NLTK and SpaCy libraries for natural language processing. The task involves downloading and preprocessing the movie_reviews dataset from NLTK, followed by tokenization and basic text cleaning using SpaCy.

# Features

• Download movie reviews dataset using NLTK.

• Preprocess and tokenize the text using SpaCy's English language model.

• Remove punctuation, stop words, and whitespace from the reviews.

# Setup Instructions
To run this project locally, follow these steps:

# Prerequisites
You need Python 3 installed on your system along with the following Python packages:

• nltk

• spacy

# Installation

1.Clone the repository or copy the script into your local environment.

2.Install the required libraries:

  pip install nltk spacy
  
3.Download the necessary NLTK and SpaCy models:

  python -m spacy download en_core_web_sm
  
4.In your Python script, import NLTK and download the movie_reviews corpus:

  import nltk
  
  nltk.download('movie_reviews')

# Running the Code

After installing the dependencies and downloading the necessary data, you can run the code by executing the script. The script will:

1.Load and preprocess the first movie review from the movie_reviews dataset.
2.Tokenize the text, removing punctuation, stop words, and whitespace.
3.Print the original text and the preprocessed tokens.


