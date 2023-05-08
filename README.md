
# Cop Data Science NLP

This repo provides some example work surrounding Data Science NLP modeling.

## Data

In order to download the data, create an account with Kaggle and download the datasets from here: https://www.kaggle.com/competitions/nlp-getting-started
Create a new top-level directory _data/_ within the repo and place the data beneath this area.

## Python, VirtualEnvironment, Jupyter

In order to create a virtual environment in which to run these notebooks do:

    >python -m venv .venv
    >source .venv/bin/activate
    >pip install --upgrade pip
    >pip install -r requirements.txt

Where _python_ points to your local python installation, recommended to be version 3.8+. In order to start the jupyter notebook server do:

    >jupyter-notebook


## Notebooks

### NLP-Getting-Started.ipynb
This notebook is meant to be a first introductin to processing text, NLP, and using machine learning on text data. This notebook covers data cleaning, embedding creation, and logistic regression with to perform binary classification.


### NLP-Huggingface.ipynb
This notebook is an extension of the previous but expanding the the most popular ML library used today, _huggingface_ , to utilize open source transformer based models. This notebook covers how to use the huggingface framework, create different type of feature embeddings, and fine tune a transformer-based model. It should be mentioned that this training can take a very long time if one does not have a GPU-enabled machine, or one with low to moderate levels of RAM. 

