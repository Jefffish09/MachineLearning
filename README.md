# MachineLearning
Some learning notes about ML.

## Binary Classification - [IMDb](https://ai.stanford.edu/~amaas/data/sentiment/) movie review dataset
| Model            | accuracy            | loss                | f1                  |Code|
| ---------------- | ------------------- | ------------------- | ------------------- |---|
| CNN              | 0.8775 (+/- 0.0076) | 0.3015 (+/- 0.0236) | 0.8749 (+/- 0.0081) |[cnn_binary_tf2.ipynb](Classification/binary/cnn_binary_tf2.ipynb)|
| LSTM             | 0.8804 (+/- 0.0076) | 0.2938 (+/- 0.0122) | 0.8784 (+/- 0.0030) |[lstm_binary_tf2.ipynb](Classification/binary/lstm_binary_tf2.ipynb)|
| CNN+LSTM         | 0.8868 (+/- 0.0051) | 0.2817 (+/- 0.0141) | 0.8817 (+/- 0.0040) |[cnn_lstm_binary_tf2.ipynb](Classification/binary/cnn_lstm_binary_tf2.ipynb)|
| BiLSTM           | 0.8841 (+/- 0.0073) | 0.2790 (+/- 0.0065) | 0.8803 (+/- 0.0045) |[bilstm_binary_tf2.ipynb](Classification/binary/bilstm_binary_tf2.ipynb)|
| BiLSTM+Attention | 0.8808 (+/- 0.0046) | 0.2855 (+/- 0.0076) | 0.8779 (+/- 0.0056) |[bilstm_attention_binary_tf2.ipynb](Classification/binary/bilstm_attention_binary_tf2.ipynb)|
| FastText         | 0.8907 (+/- 0.0038) | 0.2809 (+/- 0.0065) | 0.8869 (+/- 0.0010) |[fasttext_binary_tf2.ipynb](Classification/binary/fasttext_binary_tf2.ipynb)|
| bert_en_uncased_L-4_H-512_A-8|0.8390 (+/- 0.0077)|0.3589 (+/- 0.0097)|0.8310 (+/- 0.0109)|[bert_binary_tf2.ipynb](Classification/binary/bert_binary_tf2.ipynb)|
