# Sematic #

This Jupyter notebook represents my attempt to implement a context-enhanced question answering setup using open source tools that can be executed locally:
- The HuggingFace model [all-mpnet-base-v2](https://huggingface.co/sentence-transformers/all-mpnet-base-v2) is utilized for generating vector representations of text
- The resulting embedding vectors are stored, and a similarity search is performed using [FAISS](https://github.com/facebookresearch/faiss)
- Text generation is accomplished through the utilization of [GPT4ALL](https://github.com/nomic-ai/gpt4all).

The objective of this personal project is to address the issue of data that cannot be shared with OpenAI or similar APIs. Additionally, it serves as my initial encounter with [LangChain](https://python.langchain.com/en/latest/index.html), a framework designed for developing applications powered by language models.

## Running the notebook ##
To run the notebook, you may try accessing it through [Google Colab](https://colab.research.google.com/drive/1csJ9lzewAaBVNSO9icJC5iT7xVrUbcg0?usp=sharing) or import the .ipynb file from this repository into a new Google Colab environment. Subsequently, please refer to the instructions provided within the notebook itself and/or the accompanying [__Youtube video__](https://youtu.be/y32vbJkabCw) for guidance.