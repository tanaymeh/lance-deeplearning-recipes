## Creating Instruction dataset for LLM fine-tuning

### Overview
In this example, we will be creating an Instruction dataset for LLM fine-tuning by using the [`tatsu-lab/alpaca`](https://huggingface.co/datasets/tatsu-lab/alpaca) dataset, tokenizing it and saving it as a Lance dataset

Alpaca is a dataset of 52,000 instructions and demonstrations generated by OpenAI's text-davinci-003 engine. This instruction data can be used to conduct instruction-tuning for language models and make the language model follow instruction better.

Unlike the LLM pre-training dataset, we are preserving the samples in this example by tokenizing all values in a row in the original dataset and storing them as a row in the lance dataset. These two examples, hence, show two different approaches to converting any text dataset to lance format.

### Code and Blog
Below is the link for the Google Colab walkthrough.

<a href="https://colab.research.google.com/github/lancedb/lance-deeplearning-recipes/blob/main/examples/alpaca-dataset/alpaca-dataset.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">