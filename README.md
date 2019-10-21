# NLP sklearn

The NIPS conference (Neural Information Processing Systems) is one of the most prestigious yearly events in the machine learning community. At each NIPS conference, a large number of research papers are published. Over 50,000 PDF files were automatically downloaded and processed to obtain a dataset on various machine learning techniques. These papers discuss a wide variety of topics in machine learning, from neural networks to optimization methods and many more.

This is a diagnostic analysis of Machine Learning topics from NIPS papers data using LDA, GridSearch from sklearn, and CoherenceModel from gensim.

In the first notebook - sklearn, I use the Natural Language Processing (NLP) techniques, Latent Dirichlet allocation (LDA) and GridSearch from python's <code>sklearn</code> library to analyze machine learning topics in the NIPS papers dataset. I use the concepts of perplexity and log likelihood to find the optimal number of topics for the data. I then plot the various models that come out of the GridSearch fit against their perplexity to see which models perform best.

![](https://i.imgur.com/Ibm4gJJ.jpg)

In the second notebook - gensim, I again use LDA, this time with CorehenceModel from python's <code>gensim</code> library to analyze machine learning topics in the NIPS papers dataset. The concept of topic coherence measure is used to find the optimal number of topics for the data. Finally, I use python's LDA visualization tools to display the results of a model with the aforementioned number of topics.

![LDA Visualization](https://i.imgur.com/GuAiXBd.jpg)

Data taken from kaggle.com. Find the dataset [here](https://www.kaggle.com/benhamner/nips-papers) under papers.csv.
