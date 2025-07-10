### Sentiment classification 
In this project, a deep learning model based on the Long Short-Term Memory (LSTM) architecture was developed to perform sentiment analysis on customer reviews collected from an e-commerce platform. The goal was to automatically classify review texts into three sentiment categories: positive, neutral, or negative.

User reviews written in natural language were preprocessed before being input into the model. Preprocessing steps included:

- Removing stop words,
- Lemmatization to reduce vocabulary size and improve generalization,
- Tokenization and conversion of text into numerical sequences.
  
The model architecture features a Spatial Dropout layer, followed by an LSTM layer with 128 units and built-in regularization. This is followed by a Dense layer with 128 neurons and ReLU activation, another Dropout layer, and a final output layer with softmax activation for three-class sentiment classification.

This end-to-end pipeline enables effective sentiment classification by capturing the contextual and sequential nature of language, making it well-suited for real-world e-commerce applications.
