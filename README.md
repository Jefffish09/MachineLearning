# MachineLearning
Some learning notes about ML.

## Binary Classification - [IMDb](https://ai.stanford.edu/~amaas/data/sentiment/) movie review dataset

| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
|MLP|0.8741 (+/- 0.0099)|0.3006 (+/- 0.0118)|0.8727 (+/- 0.0070)|[mlp_binary_tf2.ipynb](Classification/binary/mlp_binary_tf2.ipynb)|
| CNN              | 0.8753 (+/- 0.0043) | 0.2992 (+/- 0.0127) | 0.8778 (+/- 0.0043) |[cnn_binary_tf2.ipynb](Classification/binary/cnn_binary_tf2.ipynb)|
| LSTM             | 0.8787 (+/- 0.0055) | 0.2953 (+/- 0.0132) | 0.8760 (+/- 0.0047) |[lstm_binary_tf2.ipynb](Classification/binary/lstm_binary_tf2.ipynb)|
| CNN+LSTM         | 0.8844 (+/- 0.0083) | 0.2828 (+/- 0.0128) | 0.8816 (+/- 0.0041) |[cnn_lstm_binary_tf2.ipynb](Classification/binary/cnn_lstm_binary_tf2.ipynb)|
| BiLSTM           | 0.8832 (+/- 0.0046) | 0.2818 (+/- 0.0088) | 0.8806 (+/- 0.0061) |[bilstm_binary_tf2.ipynb](Classification/binary/bilstm_binary_tf2.ipynb)|
| BiLSTM+Attention | 0.8848 (+/- 0.0052) | 0.2838 (+/- 0.0094) | 0.8804 (+/- 0.0021) |[bilstm_attention_binary_tf2.ipynb](Classification/binary/bilstm_attention_binary_tf2.ipynb)|
| FastText         | 0.8913 (+/- 0.0038) | 0.2807 (+/- 0.0064) | 0.8872 (+/- 0.0008) |[fasttext_binary_tf2.ipynb](Classification/binary/fasttext_binary_tf2.ipynb)|
| bert_en_uncased_L-4_H-512_A-8|Calculating|Calculating|Calculating|[bert_binary_tf2.ipynb](Classification/binary/bert_binary_tf2.ipynb)|

## Requirements

* Python 3.6
* TensorFlow 2
* [Google Colaboratory](https://colab.research.google.com/)

## License

[GPL-3.0](LICENSE)