# Training a Sigmoid with the Naver Movie Review Sentiment Dataset

The file is LSTM, BiLSTM, GRU and CNN Model in Tensorflow

## 1. How to Use
```markdowns
 1. Google Colab 
    - Using the Colab Pro version
    - Using TPU
 
 2. Dataset 
    - Naver Movie Review Sentiment
    - Train : 150,000
    - Test : 50,000 
```

## 2. Result 
### 2-1. LSTM 

   |precision|recall|f1-score|
   |------|---|---|
   |0.86|0.84|0.85|
   |0.84|0.86|0.85|
   |||0.85|

### 2-2. BiLSTM

   |precision|recall|f1-score|
   |------|---|---|
   |0.84|0.87|0.85|
   |0.86|0.83|0.85|
   |||0.85|

### 2-3. GRU

   |precision|recall|f1-score|
   |------|---|---|
   |0.83|0.87|0.85|
   |0.87|0.82|0.85|
   |||0.85|

### 2-4. CNN

   |precision|recall|f1-score|
   |------|---|---|
   |0.84|0.86|0.85|
   |0.86|0.83|0.84|
   |||0.85|
