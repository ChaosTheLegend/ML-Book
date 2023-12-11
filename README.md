# ML-Book

## План

## 1. Introduction 

Короткий обзор RNN

## 2. The Need for Attention Mechanism

Discuss the limitations of the traditional Seq2Seq model (which uses an encoder-decoder architecture). Highlight the issue of how trying to encode an entire input sequence into a single fixed-size vector (the context) can result in the loss of information, especially with long sequences.

- График как растет accuracy по отношению к количеству эпох в SimpleRNN

## 3. Introduction to Attention Mechanism:
   
Describe the concept of an attention mechanism and its purpose. Explain how attention allows the model to 'focus' on different parts of the input sequence at each step in the output sequence, alleviating the need for a single fixed context vector.

- Вставить картинку как работает LSTM

- График как растет accuracy по отношению к количеству эпох в LSTM

- График сравнение LSTM и SimpleRNN

## 4. Attention in Detail:

Dive into the mathematics behind attention. Explain key concepts such as alignment scores, softmaxing these scores to obtain the final attention weights, and creating the context vector as the weighted sum of the encoder hidden states. 
You can also describe the difference between various types of attention such as "soft" vs "hard" attention, "local" vs "global" attention, and "self" vs "encoder-decoder" attention. Each of these variations can be explored in their own subsections.

### 4.1. Alignment Scores:

Explain the concept of alignment scores, which are used to determine the importance of each encoder hidden state at each step in the output sequence. Discuss the different ways of calculating these scores, such as the dot product method, the additive method, and the multiplicative method.

### 4.2. Softmax:

Explain how the alignment scores are converted into attention weights using the softmax function. Discuss the importance of the softmax function in this context, and how it allows the model to 'focus' on different parts of the input sequence at each step in the output sequence.


## 5. Visualization of Attention:

One of the great aspects of attention is that the weights can be visualized, which can provide insight into what the model is 'focusing on' at each step. Discuss this advantage and, if possible, include examples of such visualizations in your article.


## Графики

+ Вставить картинку как работает LSTM
+ Вставить картинку как работает Attention
+ Сравнение LSTM и SimpleRNN - граффик
+ график точность по отношению к количеству эпох (LSMT, SimpleRNN)
+ потенциально добавить heatmap для 
+ Добавить поле в котором пользователь может ввести свой текст и посмотреть как модель будет предсказывать его
