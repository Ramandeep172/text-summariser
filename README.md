# TEXT-SUMMARISER

Text summariser is as the name suggests a text summarisation application. Three Natural language processing(NLP) algorithms have been implemented - textrank, latent semantic analysis and kl-sum which were chosen after researching the commonly used algorithms and comparing their accuracies, performances and popularity. 

This is a simple application written in flask which is a micro web framework of python. The website has been deployed on Heroku as well. 

# About algorithms
Test rank -> Text rank is a general purpose, graph based ranking algorithm for Natural Langauge Processing. It is an automatic summarisation technique. The algorithm is similar to google's page rank algorithm which checks the importance of a webpage by number of links associated with it. In text rank webpages are replaced by sentences. It finds the most relevant sentences in text.

KL Sum -> In mathematical statistics, the Kullback-Leiber divergence (relative entropy) is a measure of how one probability distribution is different from another. Less the divergence, more the summary and the document are similar to each other in terms of understandability and meaning conveyed. The objective of KL sum algorithm is to find a set of sentences whose length is less than L words and the unigram distribution is as similar to the source document. Unigram distribution - Unigram or n-gram in the field of computational linguistics and probability refers to a contiguous sequence of n items from a given sample of speech or text.

Latent semantic analysis -> Latent semantic analysis (LSA) is a technique in natural language processing, in particular distributional semantics, of analyzing relationships between a set of documents and the terms they contain by producing a set of concepts related to the documents and terms. LSA assumes that words that are close in meaning will occur in similar pieces of text (the distributional hypothesis). A matrix containing word counts per document (rows represent unique words and columns represent each document) is constructed from a large piece of text and a mathematical technique called singular value decomposition (SVD) is used to reduce the number of rows while preserving the similarity structure among columns. Documents are then compared by taking the cosine of the angle between the two vectors (or the dot product between the normalizations of the two vectors) formed by any two columns. Values close to 1 represent very similar documents while values close to 0 represent very dissimilar documents

# How to use 
Visit the website https://my-text-summariser.herokuapp.com/ to view the application. Fill the form as shown. Enter text or file and select the options to get required output.

# How to replicate
Basic requirements- Python 3.7 or above <br/>
Step 1. clone and download the project <br/>
Step 2. run command pip install -r requirements.txt <br/>
Step 3. run command app.py and open localhost:5000 to view the application
