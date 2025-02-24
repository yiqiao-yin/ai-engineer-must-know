# AI Basics

## What is a Transformer Model?
The transformer model is an architecture for transforming one sequence into another through mechanisms known as attention, allowing the model to weigh the influence of different parts of the input differently. It was introduced in the paper "Attention is All You Need" and is widely used for various natural language processing tasks.

## What is an Attention Layer?
An attention layer in neural networks helps the model focus on specific parts of the input sequence when generating a particular part of the output sequence. This mechanism is vital in models dealing with sequences where the relevance of input elements varies. Mathematically, attention weights \( \alpha_{ij} \) are computed using a softmax of compatibility scores between input elements \( x_i \) and output elements \( y_j \), with the context vector \( c_j \) being a weighted sum of input features based on these weights.

## What is an Embedding Layer?
An embedding layer transforms sparse, categorical input data into a dense representation of fixed size. In the context of natural language processing, it converts words or phrases into vectors of real numbers which represent these inputs in a more meaningful way for neural networks.

## What is Positional Embedding?
Positional embeddings are used in models like transformers to inject information about the position of tokens in the input sequence. They enable the model to understand the order of words or components, which is crucial for processing sequences of data where order matters.

## What are Some Tokenizers?
- **Byte Pair Encoding (BPE):** Commonly used in NLP, BPE tokenizes text by iteratively replacing the most frequent pairs of bytes with a single, unused byte.
- **WordPiece:** Often used in models like BERT, it splits words into subwords, which can represent common substructures in words.
- **SentencePiece:** A tokenizer that treats the input as a raw input stream, allowing it to learn subwords directly from the raw texts instead of pre-tokenized text.

## What is Gradient Descent?
Gradient descent is an optimization algorithm used to minimize a function by iteratively moving in the direction of steepest descent as defined by the negative of the gradient. In machine learning, it is used to update the parameters of a model. Coding it from scratch involves calculating derivatives and updating the parameters iteratively.

## What is Retrieval Augmented Generation?
Retrieval Augmented Generation (RAG) combines a retrieval mechanism with a generative model to enhance the generation process by leveraging external knowledge. The retriever fetches relevant context from a knowledge source, which is then fed into a generator to produce more informed and accurate outputs.

## What are Some Famous Agentic AI Frameworks?
- **Pydantic:** A data validation and settings management using Python type annotations.
- **FastAPI:** Leverages Pydantic for data validation and is popular for building APIs with Python based on modern design patterns.
- **Django:** Though not exclusively for agentic frameworks, it can be adapted for agent-based interactions in complex web applications.
