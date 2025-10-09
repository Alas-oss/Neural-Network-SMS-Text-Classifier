# Neural Network SMS Text Classifier
The main objective of this project was to build a binary text classification model to determine whether an SMS is spam or ham (legitimate).

## My Contribution
- Utilized the SMS Spam Collection dataset, which was already preprocessed into **train_data** and **test_data**
- Processed the text data using:
  - Tokenization
  - Padding to ensure uniform input size for the model
- Built a **Neural Network** using TensorFlow/Keras:
  - Embedding layer for representing words
  - Flatten layer
  - Denese layers with ReLU and sigmoid activations
- Trained the model on labeled SMS data
- Created a function **predicted_message()** to:
  - Take a raw SMS message as input
  - Preprocess the message similarly to the training data
  - Return a list like containing the certainty score and whether the message is spam or 'ham'
 
## Key skills developed
- Built a text classification model using deep learning
- Worked with work tokenization, embedding layers, and binary classification
- Understood span detection as a real-world NLP task
- Practiced deploying inference-ready functions for text inputs
