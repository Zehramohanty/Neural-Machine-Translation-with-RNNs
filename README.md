# Neural-Machine-Translation-with-RNNs
In Machine Translation, the goal is to convert a sentence from the source language (e.g. Cherokee) to the target
language (e.g. English). This project implements a sequence-to-sequence (Seq2Seq) network with
attention, to build a Neural Machine Translation (NMT) system. The training procedure 
for the proposed NMT system uses a Bidirectional LSTM Encoder and a Unidirectional LSTM Decoder.

Figure 1: Seq2Seq Model with Multiplicative Attention, shown on the third step of the
decoder. Note that for readability, we do not picture the concatenation of the previous
combined-output with the decoder input.
<img width="399" alt="Screenshot 2024-11-21 at 8 33 20 PM" src="https://github.com/user-attachments/assets/5e654946-4105-4b48-8491-3a9a23c36e77">


Tested using Python version 3.11.7.
