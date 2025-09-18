# RNN Text Classifier for Crocodile Species

A PyTorch-based RNN (LSTM) text classification project that predicts the common name of crocodile species based on textual features such as country/region, habitat, scientific name, and family. The project demonstrates preprocessing, tokenization, dataset handling, model training, and evaluation with professional practices like scheduler, train/eval functions, and metrics tracking.


## Features

- Tokenization using Hugging Face's `AutoTokenizer`
- LSTM-based neural network with embedding layer
- Dataset handling using `torch.utils.data.Dataset` and `DataLoader`
- Training and evaluation pipelines
- Metrics calculation: Accuracy, F1-score, Precision, Recall
- Professional practices: batch handling, padding, scheduler, GPU support


## Requirements

```txt
pandas
torch
transformers
scikit-learn
