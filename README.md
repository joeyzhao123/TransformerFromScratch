# Transformer Project

This project is an implementation of a Decoder Only Transformer from the paper "Attention is All You Need."
I followed their architecture with Multiheaded attention and the order of the layers for the most part. There were some differences since it was a Decoder Only Transformer.
I used the data from Karpathy MinGPT and followed hyperparameters consistent with those chosen for a model this size. The data is Shakespeare and the model will attempt to generate Shakespeare, although not that great since I didn't train it for many iterations or on a large model.
I also used SentencePiece to train a tokenizer on the data and tried different vocab sizes to see how they would affect the generated content.

# Results
For the most part, the results were positive. I learned a lot about writing a model as well as reinforcing my knowledge about the inner workings of a Transformer. I saw steady decreases in both training and validation loss. The quality of the generation definitely increased as I trained the model longer.

### Future Work
In the future, I might train the model until I reach see the validation acc start increasing. In addition, I want to try more tokenizers as well as make my own tokenizer to see how they affect performance.

### Getting Started

To replicate the code, you'll just want to run all of the cells from the top down. There is a cell for hyperparams that you can edit if you want to fiddle around with the settings. In addition, you can easily change the tokenizer for new data and vocab sizes.

### Prerequisites

I used the libraries
PyTorch and
Numpy
