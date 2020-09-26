**Requirements: You will need to have NLTK installed, along with downloading the corpus for stopwords. To download everything with a conda installation, run the cell below. Or reference the full video lecture**

DATA : We'll be using a dataset from the [UCI datasets](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)!
	File we are using is a TSV file
	The file we are using contains a collection of more than 5 thousand SMS phone messages.
	The first column is a label saying whether the given message is a normal message (commonly known as "ham") or "spam". The second column is the message itself.

Problem Statement:
	Using these labeled 'ham' and 'spam' examples, we'll **train a machine learning model to learn to discriminate between ham/spam automatically**. Then, with a trained model, we'll be able **to classify arbitrary unlabeled messages** as ham or spam.