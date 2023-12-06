# ML-Book

## План

## 1. Introduction

Короткий обзор RNN

## 2. The Need for Attention Mechanism

Discuss the limitations of the traditional Seq2Seq model (which uses an encoder-decoder architecture). Highlight the issue of how trying to encode an entire input sequence into a single fixed-size vector (the context) can result in the loss of information, especially with long sequences.

## 3. Introduction to Attention Mechanism:
   
Describe the concept of an attention mechanism and its purpose. Explain how attention allows the model to 'focus' on different parts of the input sequence at each step in the output sequence, alleviating the need for a single fixed context vector.

## 4. Attention in Detail:

Dive into the mathematics behind attention. Explain key concepts such as alignment scores, softmaxing these scores to obtain the final attention weights, and creating the context vector as the weighted sum of the encoder hidden states. 
You can also describe the difference between various types of attention such as "soft" vs "hard" attention, "local" vs "global" attention, and "self" vs "encoder-decoder" attention. Each of these variations can be explored in their own subsections.

## 5. Examples of Attention in Practice:
   
Discuss a few well-known models that utilize attention, such as the Transformer model (used in BERT, GPT-2), or convolutional seq2seq models. Each of these examples could include a brief overview of the model, a description of how attention is used within it, and what this attention contributes to the model's performance on relevant tasks.

## 6. Visualization of Attention:

One of the great aspects of attention is that the weights can be visualized, which can provide insight into what the model is 'focusing on' at each step. Discuss this advantage and, if possible, include examples of such visualizations in your article.
