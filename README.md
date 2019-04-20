# NLP sklearn
A diagnostic analysis of Machine Learning topics from NIPS papers data using LDA and GridSearch from sklearn.

Data taken from kaggle.com. The file is too big to upload here. Find the dataset [here](https://www.kaggle.com/benhamner/nips-papers) under papers.csv.

![](https://i.imgur.com/Ibm4gJJ.jpg)

In this notebook, I use the Natural Language Processing (NLP) techniques of Latent Dirichlet allocation (LDA) and GridSearch from python's <code>sklearn</code> library to analyze machine learning topics in the NIPS papers dataset. I use the concepts of perplexity and log likelihood to find the optimal number of topics for the data. I will then plot the various models that come out of the GridSearch fit against their perplexity to see which models perform best.
