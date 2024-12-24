#disaster_tweets

# Data loading and inspecting (Rohit Mane)
Imported required models.
Loaded train, test data,
Looked for null and duplicated values and taken required action according to it.
observed data description(mean, mode, median, max, etc) and data info.


# text Cleaning----(by kranti kalyane)
 Removed Hashtags, URLs, Punctuation, and Numbers using regular expressions.
 Applied Word Tokenization to split text into individual words.
 used POS Tagging to assigns a grammatical label to each word in a sentence, such as noun, verb, or adjective. It helps identify the role of words in the text 

# cleaning and vectarization( by ashish gutte)
Function remove_stopwords removes common English stopwords from text using NLTK.Function lemmatize_text applies lemmatization using NLTK's WordNetLemmatizer to reduce words to their base form.Uses the spaCy pre-trained model en_core_web_md to generate word embeddings (vectors) for each word in the text.
Combines word vectors to represent text numerically.The target column from the training data is saved as train_y for modeling.

# Data visualization & Data cleaning ( Gaurav Gadhave )
1)Target Distribution:
Visualized the distribution of the target variable (0 and 1) using a pie chart and a count plot. This helped understand the balance between the classes.

2)Missing Data Analysis:
Created a heatmap to identify missing values in the dataset. This step highlighted patterns of missing data, aiding in determining necessary preprocessing steps.

3)Frequency Analysis:
Analyzed the frequency of unique values in the location and keyword columns to identify common entries and their significance in the dataset.
