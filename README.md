# Speaker Classification using Conformer 
Task Introduction
This project focuses on speaker classification using self-attention mechanisms inspired by the transformer architecture. The concept of self-attention was introduced in Google's work, !["Attention is All You Need]([url](https://arxiv.org/pdf/1706.03762.pdf))
  combining the strengths of Recurrent Neural Networks (RNN) and Convolutional Neural Networks (CNN) for parallelized sequence processing.

# Main Goal
The primary objective is to learn how to implement and utilize transformers for multiclass classification tasks, building upon the knowledge gained in previous tasks such as phoneme classification.

# Phoneme Classification 
A phoneme is defined as a unit of speech sound in a language that can distinguish one word from another.

![image](https://github.com/Sajidcodes/Conformer/assets/101083684/5a25b566-3ae7-475c-be85-958dd65090ed)


# Speaker Classification
The focus is on multiclass classification for speaker classification. The goal is to predict the speaker from a given speech segment, treating each speech as a sequence of audio features.

![image](https://github.com/Sajidcodes/Conformer/assets/101083684/b07e9997-60b6-4676-8a7a-28b9b642ff2a)

# Data
Training Set: 62,464 processed audio features with labels
Test Set: 6,944 processed audio features without labels
Label: 600 speakers, where each class represents a unique speaker
It is recommended to download the data and create a copy on your own drive for reading. Due to quota limitations, it's advised to avoid excessive downloads.
Data Segmentation during Training
To facilitate data segmentation during training, a sample code is provided. The code demonstrates how to use the transformer architecture for speaker classification.

![image](https://github.com/Sajidcodes/Conformer/assets/101083684/f91beda2-9738-4989-ad8d-4abf301ee3bf)



# Food for Thought
Explore the conformer architecture (refer to the paper and function).
Investigate the additive margin softmax (refer to the paper).
Good luck with the speaker classification task! If you have any questions, feel free to reach out.





