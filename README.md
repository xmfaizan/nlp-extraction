One-hot encoding, TF-IDF (Term Frequency-Inverse Document Frequency), and Bag of Words (BoW) are commonly referred to as feature extraction or feature representation techniques in Natural Language Processing (NLP). 
These techniques are used to transform text data into numerical representations that can be used as input for machine learning models.

    One-hot Encoding:
        Represents text data by converting each word into a vector of zeros and ones.
        Each word is represented by a vector where the index corresponding to the word is set to 1, and all other indices are set to 0.
        Used to handle categorical data in many applications, including NLP.

    Bag of Words (BoW):
        Represents text by counting the frequency of words in a document.
        Ignores grammar and word order, focusing only on word occurrence.
        Produces a sparse matrix where each row represents a document and each column represents a word.

    TF-IDF (Term Frequency-Inverse Document Frequency):
        A statistical measure used to evaluate the importance of a word in a document relative to a collection of documents (corpus).
        Combines term frequency (TF) and inverse document frequency (IDF) to reduce the weight of common words and emphasize rarer, more informative words.
        Helps in highlighting important words while minimizing the influence of frequent but less informative words.
