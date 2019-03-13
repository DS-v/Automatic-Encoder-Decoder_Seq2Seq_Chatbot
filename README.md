# Automatic Encoder-Decoder Seq2Seq: English Chatbot
## エンコーダ・デコーダLSTMによるSeq2Seqによる英語チャットボット
![](https://cdn-images-1.medium.com/max/2600/1*sO-SP58T4brE9EHazHSeGA.png)

## Motivation

Seq2seq is Sequence to Sequence model, input and output of the model are time series data, and it converts time series data into another time series data.   
Pass the data you want to convert as an input to Encoder, process it with Encoder, pass the processing result to Decoder, and Decoder outputs the conversion result of the input data.   
Encoder and Decoder use RNN and process given time series data respectively.

## Technical Preferences

| Title | Detail |
|:-----------:|:------------------------------------------------|
| Environment | MacOS Mojave 10.14.3 |
| Language | Python |
| Library | Kras, scikit-learn, Numpy, matplotlib, Pandas, Seaborn |
| Dataset | [Tab-delimited Bilingual Sentence Pairs](http://www.manythings.org/anki/) |
| Algorithm | Encoder-Decoder LSTM |

## Refference

- [Machine Translation using Sequence-to-Sequence Learning](https://nextjournal.com/gkoehler/machine-translation-seq2seq-cpu)
- [Chatbots with Seq2Seq Learn to build a chatbot using TensorFlow](http://complx.me/2016-06-28-easy-seq2seq/)
- [Generative Model Chatbots](https://medium.com/botsupply/generative-model-chatbots-e422ab08461e)
- [How I Used Deep Learning To Train A Chatbot To Talk Like Me (Sorta)](https://adeshpande3.github.io/How-I-Used-Deep-Learning-to-Train-a-Chatbot-to-Talk-Like-Me)
