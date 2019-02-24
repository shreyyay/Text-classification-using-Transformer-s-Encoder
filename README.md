# Text-classification-using-Transformer-s-Encoder

Only encoder part of Transformer model is used for classification.

No need for masking.

Multihead attention and feedforward network  is used to extract features.

Finally, linear layer to get logits.

Only one layer of encoder is used.

Adam optimizer is used with initial learning rate. 0.0003. Reducing by half every 1/3 epochs.

The dataset consist of news articles with corresponding labels. 
