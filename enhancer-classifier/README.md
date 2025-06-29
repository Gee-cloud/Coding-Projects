# Enhancer Sequence Classifier using CNN

This project uses a Convolutional Neural Network to distinguish human genomic enhancers from random non-enhancer sequences.

## Dataset
- Positive: 63,285 human enhancer sequences (FANTOM5)
- Negative: 63,285 random genomic regions from hg38

## Model
- 1D CNN with embedding + convolution + dense layers
- Accuracy: ~75% on validation set

