# Term-Term Co-occurrence Matrix

A term-term co-occurrence matrix is a method of analyzing text data to determine the frequency of words occurring together in a given corpus. In this method, a matrix is constructed where the rows and columns represent the individual terms or words in the corpus, and the cells contain the frequency of co-occurrence of the corresponding pair of terms.

To construct a term-term co-occurrence matrix with a window of ±3, we first divide the text into a sequence of words. Then, we slide a window of size 7 (3 words before and after the central word) across the text, and for each window, we record the co-occurrence of the central word with the surrounding 6 words.

The term-term co-occurrence matrix with a window of ±3 can be used to perform various text analysis tasks such as semantic similarity, topic modeling, and clustering. It provides a way to extract valuable information from a corpus of text data and to gain insights into the relat
