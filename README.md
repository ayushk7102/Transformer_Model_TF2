# Transformer_Model_TF2
Building a conversational model with a transformer via TensorFlow 2.

**Dataset**

Currently trained on the Convokit Movie-Dialogs Corpus (https://convokit.cornell.edu/documentation/movie.html)

**Model**

Consists of an encoder and decoder. An input embedding is positionally encoded. Multi-head attention in the encoder, and masked multi-head attention in the decoder (look ahead mask and padding mask). Dropout layer implemented in decoder to prevent overfitting.

Helpful resources: _Transformer Chatbots with TensorFlow 2.0_ ( Bryan M. Li, TensorFlow blog), _Illustrated Guide to Transformers_, https://www.youtube.com/watch?v=4Bdc55j80l8 (Michael Phi, Youtube)
