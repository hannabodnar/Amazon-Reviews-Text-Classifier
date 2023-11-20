# Amazon-Reviews-Text-Classifier
### Objective
This project aims to construct a text classifier that will predict if a product review is positive or negative based on the text of that review. The outline is as follows:
- Import JSON file and create a dataframe of its content.
- Preprocess and split the data into training and testing sets.
- Initialize Tokenizer with parameters and paddings.
- Build a Sequential model featuring an Embedding layer, two bidirectional LSTM layers, a Dense layer, and an output Dense layer.
- Visualize results through accuracy and loss.
- Predict new reviews. 

### Dataset
The Amazon Appliance Reviews dataset from the original [Amazon Reviews](https://nijianmo.github.io/amazon/index.html) dataset.
