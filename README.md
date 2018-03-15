# Analyze Fake News using IBM Watson Natural Language Understandings
Menace caused by fake news are far more reaching & impacting and poses major global risks to societies. Understanding the patterns, trends and other insights about fake news is very essential in understanding its impact on the society.

This notebook shows how to enrich & analyze a fake news dataset using Watson Natural Language Understanding (NLU) API to detect interesting insights and anomalies. We will analyze fake news dataset availble from https://www.kaggle.com/mrisdal/fake-news using Watson NLU, IBM Watson Studio, Python, Matplotlib, Seaborn and Pixie Dust. Watson NLU is one of the API's on the Watson Developer Cloud platform that let's you analyze text to extract meta-data from content such as concepts, entities, keywords, categories, sentiment, emotion, relations, semantic roles, using deep natural language understanding.

We'll load the fake news data in CSV format using Pandas and do some basic descriptive analysis. Then, we will then enrich the columns in the dataset using Watson NLU API to get the sentiment, document emotion, keywords, and entities. We will then perform additonal descriptive analysis on the enriched dataset. We will use for the purposes of this notebook 3 visualization libraries. The goal is to show the art of the possible with each one of these. This notebook contains the steps and code to get you started with visualizing data with all these libraries.

1. Matplotlib - a plotting library for the Python and its numerical mathematics extension NumPy
2. Seaborn - a Python visualization library based on matplotlib.
3. PixieDust is an open source Python helper library that works as an add-on to Jupyter notebooks to improve the user experience of working with data.

## Steps
1. Download the raw dataset (CSV file) from https://www.kaggle.com/mrisdal/fake-news
2a. Create a Watson Studio account, if you don't have one. Or use your existing login.
2b. You can also run this notebook locally on you Jupyter setup. You will need Python 3.5+
3. Create a new project in Watson Studio, upload the dataset, and create a new notebook from URL https://github.com/swamichandra/AnalyzeFakeNews/blob/master/Analyze%20Fake%20News%20with%20Watson%20NLU.ipynb
