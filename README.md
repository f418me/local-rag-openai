# local-rag-openai

What is RAG?

Retrieval-Augmented Generation (RAG) is a powerful method that combines the capabilities of information retrieval from large datasets with text generation. Unlike traditional AI models that rely solely on pre-trained data, RAG leverages external data sources to enhance its outputs. This approach uses external information to answer queries, making the generation process more contextually rich and relevant.

How does it work?

Documents or other content are broken down into small sections or "chunks." These chunks are then transformed into what are known as "embeddings," and stored in a vector database. Embeddings are vector representations of text, offering a way to preserve the content in a formatted, searchable format. This setup allows RAG to retrieve pertinent information effectively when generating text responses.

This repository demonstrates a simple example of how RAG can be implemented to create meaningful and contextually appropriate responses by integrating retrieval with generative models.

See also:

[f418.me - Bitcoin AI Chatbot](https://f418.me/bitcoin-ai-chatbot-rag-retrieval-augmented-generation/)


## How to use

### Prerequisites
In this example some pdf files with data are needed. Any pdf which contains some readable text can be taken.
We use a pdf representation of the [The Genesis Book](https://thegenesisbook.com) which can be generated from the google docs here
[The Genesis Book - Google Doc](https://drive.google.com/drive/folders/1j7PDr7uTNsJs3CmCmtB0vLjmkKz4GOnQ).


### Setup and install the requirements:

```
git https://github.com/f418me/local-rag-openai.git
cd local-rag-openai
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```


### Run jupyter notebook

```jupyter notebook```


## Credits

This example was provided in the following course, which is highly recommended:

[llamaindex-course](https://www.udemy.com/course/llamaindex/learn/lecture/40680138)