# Text-generation-with-transformers

ChatGPT2 by OpenAI has created a big change in the field of Artificial Intelligence. It is open sourced transformed based model trained on millions of web pages and papers.

What are transformers? A transformer is a deep learning model that uses the mechanism of self-attention, differentially weighting the significance of each part of the input (which includes the recursive output) data. It is used primarily in the fields of natural language processing (NLP) and computer vision (CV).

Self-attention is a mechanism for the network to contextualize words by paying attention to other words that make up its context in a body of text. The idea of self-attention is similar to the idea of attention introduced earlier, except that it’s used to contextualize words in a sentence as opposed to aligning words across translation as shown above.

Consider these two sentences:

The doors of the jaguar are open.
The jagaur howled loudly.
The first sentence is talking about a car and the second is talking about the animal. To solve this problem, transformer models use neural networks to generate a vector and key pair.

Generative pretrained transformers(GPT) are a family of Transformer models trained by OpenAI for Language Modeling tasks. Few decoding methods can be applied on these models to get even better results.

In this notebook we can observe different decoding methods such as Greedy search, Beam search, Top-K sampling and Top-p sampling that are applied on the models from transformers library.
