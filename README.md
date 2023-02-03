# Word Representation in Biomedical Domain

The repository of the NLP project for the 2023 Imperial Data Science Winter School. In this project, we will be using the CORD-19 dataset to study the word representation in biomedical domain.

## Setup

1. create a virtual environment with python 3.7 or newer

   ```bash
   python3 -m venv .venv
   ```

1. install the requirements

   ```bash
   pip install -r requirements.txt
   ```

1. activate the virtual environment

   ```bash
   source .venv/bin/activate
   ```

1. download the CORD-19 dataset

   ```bash
   wget -P ./data/ https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/2021-07-26/document_parses.tar.gz
   tar -xf ./data/document_parses.tar.gz
   ```

1. download the NLTK data

   ```bash
   python3 -m nltk.downloader -d ./data/nltk_data all
   ```

1. download the wikitext-103 dataset

   ```bash
   wget -P ./data/ https://s3.amazonaws.com/research.metamind.io/wikitext/wikitext-103-raw-v1.zip
   unzip ./data/wikitext-103-raw-v1.zip
   ```

1. run the notebook

   ```bash
   jupyter notebook
   ```
