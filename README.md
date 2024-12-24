#disaster_tweets













# text Cleaning----
 Removed Hashtags, URLs, Punctuation, and Numbers using regular expressions.
 Applied Word Tokenization to split text into individual words.
 used POS Tagging to assigns a grammatical label to each word in a sentence, such as noun, verb, or adjective. It helps identify the role of words in the text 

# cleaning and vectarization
Function remove_stopwords removes common English stopwords from text using NLTK.Function lemmatize_text applies lemmatization using NLTK's WordNetLemmatizer to reduce words to their base form.Uses the spaCy pre-trained model en_core_web_md to generate word embeddings (vectors) for each word in the text.
Combines word vectors to represent text numerically.The target column from the training data is saved as train_y for modeling.
