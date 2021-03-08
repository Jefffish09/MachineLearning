# MachineLearning
Some learning notes about ML.

## Binary Classification - [IMDb](https://ai.stanford.edu/~amaas/data/sentiment/) movie review dataset

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|MLP|0.8734 (+/- 0.0028)|0.2989 (+/- 0.0053)|0.8734 (+/- 0.0059)|[mlp_binary_tf2.ipynb](Classification/binary/mlp_binary_tf2.ipynb)|
| CNN              | 0.8737 (+/- 0.0045) | 0.2997 (+/- 0.0107) | 0.8745 (+/- 0.0039) |[cnn_binary_tf2.ipynb](Classification/binary/cnn_binary_tf2.ipynb)|
| LSTM             | 0.8754 (+/- 0.0035) | 0.3043 (+/- 0.0125) | 0.8753 (+/- 0.0047) |[lstm_binary_tf2.ipynb](Classification/binary/lstm_binary_tf2.ipynb)|
| CNN+LSTM         | 0.8824 (+/- 0.0027) | 0.2863 (+/- 0.0051) | 0.8832 (+/- 0.0032) |[cnn_lstm_binary_tf2.ipynb](Classification/binary/cnn_lstm_binary_tf2.ipynb)|
| BiLSTM           | 0.8785 (+/- 0.0034) | 0.2892 (+/- 0.0091) | 0.8778 (+/- 0.0045) |[bilstm_binary_tf2.ipynb](Classification/binary/bilstm_binary_tf2.ipynb)|
| BiLSTM+Attention | 0.8798 (+/- 0.0039) | 0.2892 (+/- 0.0105) | 0.8795 (+/- 0.0044) |[bilstm_attention_binary_tf2.ipynb](Classification/binary/bilstm_attention_binary_tf2.ipynb)|
| FastText         | 0.8866 (+/- 0.0009) | 0.2842 (+/- 0.0008) | 0.8867 (+/- 0.0012) |[fasttext_binary_tf2.ipynb](Classification/binary/fasttext_binary_tf2.ipynb)|
| bert_en_uncased_L-4_H-512_A-8|0.8438 (+/- 0.0051)|0.3598 (+/- 0.0043)|0.8379 (+/- 0.0090)|[bert_binary_tf2.ipynb](Classification/binary/bert_binary_tf2.ipynb)|

## Multiclass Classification - [US Consumer Finance Complaints](https://www.kaggle.com/cfpb/us-consumer-finance-complaints)

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|CNN|0.8317 (+/- 0.0042)|0.5488 (+/- 0.0097)|0.8252 (+/- 0.0062)|[cnn_multiclass_tf2.ipynb](Classification/multiclass/cnn_multiclass_tf2.ipynb)|
|bert-base-uncased|0.8632|0.4689|0.8611|[bert_multiclass_tf2.ipynb](Classification/multiclass/bert_multiclass_tf2.ipynb)|

## Named Entity Recognition - [GMB(Groningen Meaning Bank) corpus](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|BiLSTM|0.9968|0.0168|0.7865|[bilstm_ner_tf2.ipynb](NER/bilstm_ner_tf2.ipynb)|
|bert-base-cased - pytorch|0.9626|0.1276|0.8263|[bert_ner_pytorch.ipynb](NER/bert_ner_pytorch.ipynb)|
|bert-base-uncased - simpletransformers|0.9692|0.0994|0.8287|[bert_ner_simpletransformers.ipynb](NER/bert_ner_simpletransformers.ipynb)|

## Requirements

* Python 3.6
* TensorFlow 2
* [Google Colaboratory](https://colab.research.google.com/)

## License

[GPL-3.0](LICENSE)