# RNN Text Generation Project

## Project Description
This project demonstrates text generation using Recurrent Neural Networks (RNN) in Python with TensorFlow. The model is trained on a small dataset to predict the next word in a sequence, showcasing the capabilities of RNNs.

## Model Architecture
- **Embedding Layer:** Converts words to vectors.
- **LSTM Layer:** Learns dependencies in the sequence.
- **Dense Layer:** Generates probabilities for the next word with softmax activation.

## Training
The model was trained for 100 epochs, achieving an accuracy of approximately 8%.

## Results
After training, the model generates text based on a seed text. Although the accuracy is limited due to the small dataset and simple architecture, the project serves as a good starting point for text generation tasks using RNNs.

## Future Work
- Expanding the dataset
- Increasing model complexity
- Further hyperparameter tuning

## Usage
To run the project, open the Jupyter Notebook and follow the steps to preprocess data, train the model, and generate text.

## Files
- `RNN_Text_Generation_Project.ipynb`: The main Jupyter Notebook for the project.
