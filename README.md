# MachineLearning
Some learning notes about ML.

## Binary Classification - [IMDb](https://ai.stanford.edu/~amaas/data/sentiment/) movie review dataset

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|MLP|0.8737 (+/- 0.0024)|0.3006 (+/- 0.0049)|0.8747 (+/- 0.0032)|[mlp_binary_tf2.ipynb](Classification/binary/mlp_binary_tf2.ipynb)|
| CNN              | 0.8739 (+/- 0.0030) | 0.3022 (+/- 0.0068) | 0.8754 (+/- 0.0051) |[cnn_binary_tf2.ipynb](Classification/binary/cnn_binary_tf2.ipynb)|
| LSTM             | 0.8749 (+/- 0.0051) | 0.3030 (+/- 0.0096) | 0.8749 (+/- 0.0044) |[lstm_binary_tf2.ipynb](Classification/binary/lstm_binary_tf2.ipynb)|
| CNN+LSTM         | 0.8815 (+/- 0.0027) | 0.2878 (+/- 0.0042) | 0.8815 (+/- 0.0032) |[cnn_lstm_binary_tf2.ipynb](Classification/binary/cnn_lstm_binary_tf2.ipynb)|
| BiLSTM           | 0.8792 (+/- 0.0026) | 0.2883 (+/- 0.0036) | 0.8787 (+/- 0.0041) |[bilstm_binary_tf2.ipynb](Classification/binary/bilstm_binary_tf2.ipynb)|
| BiLSTM+Attention | 0.8787 (+/- 0.0033) | 0.2901 (+/- 0.0062) | 0.8773 (+/- 0.0052) |[bilstm_attention_binary_tf2.ipynb](Classification/binary/bilstm_attention_binary_tf2.ipynb)|
| FastText         | 0.8865 (+/- 0.0010) | 0.2841 (+/- 0.0008) | 0.8866 (+/- 0.0011) |[fasttext_binary_tf2.ipynb](Classification/binary/fasttext_binary_tf2.ipynb)|
| bert_en_uncased_L-4_H-512_A-8|0.8404 (+/- 0.0066)|0.3591 (+/- 0.0052)|0.8331 (+/- 0.0098)|[bert_binary_tf2.ipynb](Classification/binary/bert_binary_tf2.ipynb)|

## Multiclass Classification - [US Consumer Finance Complaints](https://www.kaggle.com/cfpb/us-consumer-finance-complaints)

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|CNN|0.8310 (+/- 0.0022)|0.5522 (+/- 0.0072)|0.8243 (+/- 0.0038)|[cnn_multiclass_tf2.ipynb](Classification/multiclass/cnn_multiclass_tf2.ipynb)|
|bert-base-uncased|0.8622|0.4564|0.860|[bert_multiclass_tf2.ipynb](Classification/multiclass/bert_multiclass_tf2.ipynb)|

# Named Entity Recognition - [GMB(Groningen Meaning Bank) corpus](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|BiLSTM|0.9968|0.0120|0.7886|[bilstm_ner_tf2.ipynb](NER/bilstm_ner_tf2.ipynb)|

## Requirements

* Python 3.6
* TensorFlow 2
* [Google Colaboratory](https://colab.research.google.com/)

## License

[GPL-3.0](LICENSE)